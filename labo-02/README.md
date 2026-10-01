# Labo 2 - reflecties

Naam: (jouw naam)

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: alle links die in de header in de navbar in de unorderd list en daarvan de list items zijn worden hiermee aangesproken 
- b. `article > p`: hier wordt alleen het buitenste niveau van het article aangesproken
- c. `.uren li:nth-child(3)`: enkel de 3de list item in de ul met de class uren
- d. `h2 ~ p`: selecteert elke p tag na een h2 tag
- e. `.rassen li:first-child`: selecteert de eerste list item in de ul rassen

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 | groen | a | alle links worden groen van font kleur | juist |
| 2 | blauw | de 2de class v2-tekst | de tekst krijgt de kleur blauw | juist |
| 3 | rood | .opvallend | de tekst met class opvallend wordt rood | juist |
| 4 | rood | .v4 a | enkel de tag a wordt rood | juist |
| 5 | blauw | #v5-tekst | de tekst met de id wordt blauw | juist |
| 6 | rood en blauw | .v6 en .v6-tekst | alles wordt rood behalve de tekst die wordt geoveride naar blauw | juist |
| 7 | rood | .v7 | alles wordt rood dat in de class .v7 staat | |
| 8 | blauw | style in de tag | de tekst wordt blauw want de style in de tag krijgt voorang | juist |
| 9 | rood | h3 met important | door de important wordt het rood en vallen alle andere functies voor de kleur | juist |
| 10 | groen | color groen | door de fout kan de rest niet worden uitgevoerd | juist |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
- Wat verandert er in je site als je één token wijzigt?

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. 
2. 
3. 
4. 
5. 
