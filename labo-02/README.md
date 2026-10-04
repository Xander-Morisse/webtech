# Labo 2 - reflecties

Naam: (jouw naam)

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: line 16-18, hij raakt iedere attribute in li van ul van nav van header.
- b. `article > p`:  Hij raakt alle direct childs van article die het element p zijn.
- c. `.uren li:nth-child(3)`: het derde kind van de li van de class uren. 
- d. `h2 ~ p`: Iedere p na h2 binnen dezelfde parent.
- e. `.rassen li:first-child`: Iedere first:child die een li is van class rassen dit geldt over iedere first li van zijn ouder ook ul binnen ul.

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 | groen | specificiteit | groen | ja |
| 2 | blauw | volgorde | blauw | ja |
| 3 | rood | specificiteit | rood | ja |
| 4 | rood | volgorde | rood | ja |
| 5 | blauw | specificiteit | blauw | ja |
| 6 | blauw | specificiteit | blauw | ja |
| 7 | zwart | herkomst | rood | nee | (class=vraag v7 zorgt voor de classes: vraag-v7, vraag, v7)
| 8 | blauw | herkomst | blauw | ja |
| 9 | blauw | specificiteit | rood | nee | (voorbij de important gelezen)
| 10 | blauw | volgorde | blauw | ja |

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
