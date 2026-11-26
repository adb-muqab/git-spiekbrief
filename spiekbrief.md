# Spiekbrief Git en GitHub, versie van de website
## 1. Clone, commit, push en pull
Met clone download je een volledige kopie van een online project naar je eigen computer zodat je eraan kunt werken. Als je zelf iets hebt aangepast in je code, sla je die updates met commit op als een soort vast savepoint op je eigen laptop. Met push stuur je die opgeslagen updates van jouw computer naar het online platform (zoals GitHub) zodat de rest van je team ze ook ziet. Omgekeerd haal je met pull de nieuwste aanpassingen van anderen van het online platform naar jouw eigen computer, zodat jouw versie weer helemaal up-to-date is.
## 2. Een goed commitbericht.
Waarom het ene beter is dan het andere:
Het goede voorbeeld vertelt meteen wat je precies hebt veranderd en waarom, waardoor jij en je teamgenoten later makkelijk kunnen terugvinden waar een bepaalde aanpassing is gemaakt. Het slechte voorbeeld is veel te vaag, waardoor niemand later nog snapt wat er in die versie eigenlijk is gebeurd als er plots een fout in de code zit.
## 3. Gitignore
Een .gitignore-bestand is een simpele tekstlijst waarin je aangeeft welke bestanden of mappen (zoals tijdelijke files of wachtwoorden) Git volledig moet negeren, zodat ze niet per ongeluk mee worden geüpload naar je online project.
## 4. Pull
Er zijn net nieuwe wijzigingen (van je docent of groepsgenoten) online gezet, waardoor de versie op je eigen computer niet meer gelijkloopt met de meest recente versie op het platform. Daarom moet je aan het begin van elke les altijd eerst pullen om die laatste updates binnen te halen, zodat je direct in de nieuwste code werkt en vervelende foutmeldingen (merge conflicts) voorkomt
## 5. Terugdraaien
Een foute commit verdwijnt niet uit de geschiedenis van Git omdat Git is ontworpen om een betrouwbaar en volledig overzicht te behouden van alle wijzigingen die ooit zijn gedaan. Als je een commit terugdraait met een revert, wist Git de oude fout niet, maar voegt het juist een nieuwe commit toe die de wijziging ongedaan maakt. Zo blijft de volledige tijdlijn netjes bewaard en kun je altijd achterhalen wat er is misgegaan en hoe dat is opgelost.
## 6. Branches en pull
Wat is een branch: Een branch is een afgesplitste tak van je project waarin je veilig aan nieuwe dingen kunt werken zonder dat je de hoofdcode kapotmaakt.
Waarom main de werkende versie blijft: De main-branch bevat altijd de stabiele en geteste versie van je werk, zodat je zeker weet dat de basis altijd blijft functioneren.
Wat is een pull request: Een pull request is een verzoek om jouw gewijzigde branch te controleren en samen te voegen met de main-branch.
