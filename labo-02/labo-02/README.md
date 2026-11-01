# Labo 2 - reflecties

Naam: (jouw naam)

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`:Raakt alle links in de navigatie.
- b. `article > p`:Raakt alle paragrafen die rechtstreeks in een article staan. 
- c. `.uren li:nth-child(3)`:Raakt het derde lijstitem in de lijst met class uren. 
- d. `h2 ~ p`:Raakt alle paragrafen die na een h2 komen en dezelfde ouder hebben.
- e. `.rassen li:first-child`:Raakt het eerste lijstitem binnen een lijst in het element met class rassen.

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 |Groen |Herkomst| Groen | Ja 
| 2 |Blauw |Volgorde | Blauw | Ja|
| 3 |Rood | Specificteit |Rood| Ja|
| 4 | Rood | Volgorde |Rood |Ja |
| 5 | Blauw| Specifiteit| Blauw |Ja |
| 6 |Blauw |Specifiteit |blauw |Ja |
| 7 |Rood |overerving | Rood | Ja |
| 8 | Blauw |Herkomst | Blauw |Ja |
| 9 | Rood |Important |Rood |Ja |
| 10|Groen|Syntaxfout |Groen |Ja |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)
Alles juist. Vraag 10 duurde het langst omdat ik moest zoeken naar de fout in de CSS-regel en aandacht moest besteden aan de ontbrekende puntkomma.
## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?
Ik gebruikte nav a omdat alle links zich binnen het nav-element bevinden. Een extra class was daarom niet nodig.
De opmaak van de titels en de prijzen kostte mij het meeste tijd. Ik moest verschillende kleuren en lettergewichten vergelijken met het voorbeeld voordat het resultaat overeenkwam.
## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
- Wat verandert er in je site als je één token wijzigt?
Ik gebruikte een papierkleur, een inktkleur en een accentkleur. Zo kan ik kleuren centraal beheren en gemakkelijk hergebruiken in de hele website.
Wanneer ik één token wijzig, veranderen alle elementen die dat token gebruiken automatisch mee. Daardoor kan ik snel de stijl van de volledige website aanpassen.
## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. Het model gebruikte CSS-variabelen om kleuren centraal te beheren.
2. Het model gebruikte selectors zoals nav a zonder extra classes.
3. Hover- en focusstijlen werden toegevoegd voor links.
4. Afwisselende achtergrondkleuren werden gemaakt met nth-child(odd).
5. Het model gebruikte geen !important, waardoor de CSS eenvoudiger te onderhouden blijft.
