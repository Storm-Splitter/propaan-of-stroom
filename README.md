# Propaan of stroom

Rekentool voor een vervangingsbesluit: de geiser van een weinig gebruikt pand
op propaan heeft gebreken en de rookgasafvoer moet vervangen worden. Vijf routes
uit die situatie, doorgerekend op investering én exploitatie over vijftien jaar.

**[installatie-doorn.html](installatie-doorn.html)** is de hele tool. Eén bestand,
geen build-stap, geen afhankelijkheden buiten Google Fonts. Openen in een browser
volstaat.

## Wat het doet

Elke kostenpost begint als een bandbreedte tussen een gunstig en een ongunstig
scenario. Vul je een offertebedrag in, dan vervangt dat de schatting voor die
post en krimpt de bandbreedte van die optie zichtbaar. Zo zie je in één oogopslag
hoeveel van de uitkomst nog op aannames rust en hoeveel al vaststaat.

De uitgangspunten zijn aanpasbaar: verbruik, tarieven, rendementen, de COP van de
warmtepompboiler en de looptijd. De tankhuur voor propaan heeft een eigen schuif,
omdat die de uitkomst het sterkst verschuift — tussen €0 en €250 per jaar
wisselen vier van de vijf opties van plaats.

Wat je invult blijft in je eigen browser bewaard; er gaat niets naar een server.

## De vijf routes

1. Vervangen — geiser en rookgasafvoer, blijft op propaan
2. Upgraden — warmtepompboiler, all-electric
3. Upgraden — elektrische boiler, all-electric
4. Hybride — koken op gas, warmtepompboiler voor tapwater
5. Hybride, eenvoudig — koken op gas, elektrische boiler

Opties 4 en 5 ontlopen de duurste post uit optie 1: koken op gas houden betekent
dat de rookgasafvoer alleen dichtgezet hoeft te worden in plaats van vervangen.

## Let op

De bedragen zijn indicatieve marktranges, geen offertes, en alles is inclusief
btw. De brondocumenten met persoonsgegevens staan bewust niet in deze repository.
