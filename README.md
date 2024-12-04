# brp-personen-amsterdam
Repository met de aanvullingen en beperkingen die Amsterdam stelt op de BRP API

API voor het bevragen van personen uit de basisregistratie personen (BRP), inclusief de registratie niet-ingezeten (RNI). Met deze API kun je personen zoeken en actuele gegevens over personen, kinderen, partners en ouders raadplegen.
Gegevens die er niet zijn of niet actueel zijn krijg je niet terug. Had een persoon bijvoorbeeld een verblijfstitel die nu niet meer geldig is, dan wordt die verblijfstitel niet opgenomen. In partners wordt alleen de actuele of de laatst ontbonden partner geleverd.

Dit is de variant voor de gemeente Amsterdam waarbij een koppeling is gelegd tussen de autorisaties zoals beschikbaar in de Entra omgeving van tenant amsterdam.nl en de filters die op de HC API toegepast dienen te worden in verband met dataminimalisatie.
Plus een aantal headers die verplicht zijn om aan te leveren in het kader van protocollering.
