# Labo 4 - Grid voor de pagina, flexbox voor de rij: vijf nabouw-opdrachten: modeloplossing

Dit is een mogelijke oplossing van labo 4, niet de enige. Vergelijk ze met je eigen werk: niet om over te nemen, maar om te zien waar jouw CSS afwijkt en of dat erg is. Een andere weg naar hetzelfde screenshot is niet fout, zolang ze uit hoofdstuk 4 komt; een weg die de regels breekt (een gewijzigde `index.html`, marges in plaats van `gap`, floats, `inline-block` voor een rij, id-selectors, `!important`) wel. De HTML-bestanden en `reset.css` zijn identiek aan de starter. De verwijzingen (4.3, F4.2) zijn naar de syllabus.

## 1. Drie kolommen
- Op welk element staat display: flex, en op welke elementen staat flex? Waarom staan die twee niet op hetzelfde element?
  display: flex staat op main. flex staat op de drie kolommen. De container bepaalt de layout en de items bepalen hoeveel ruimte ze innemen.


## 2. Navigatiebalk
- Welke property verdeelt de ruimte langs de hoofdas, en welke lijnt uit op de kruisas?
  justify-content verdeelt de ruimte langs de hoofdas. align-items zorgt voor de uitlijning op de kruisas.

- Wat gebeurt er met de links als je gap vervangt door margin-right op elke li?
  Dan krijgt ook het laatste item een marge. Met gap blijft de ruimte gelijk verdeeld tussen de elementen.


## 3. Mondriaan
- Welke twee vlakken moest je expliciet plaatsen, en waarom volstond de impliciete vulling voor de andere vier?
  De brede vlakken moesten expliciet geplaatst worden met grid-column. De andere vlakken werden automatisch ingevuld door de grid.

- Waarom is gap hier beter dan een border op elk vlak?
  Met gap krijg je overal even brede lijnen tussen de vlakken zonder dubbele randen.

## 4. Trap
- Wat zie je als je de grid-row-declaraties weghaalt, en waarom?
  Dan komen alle treden op de eerste rij terecht omdat de browser de elementen automatisch plaatst volgens de DOM-volgorde.

- Wat betekent grid-column: 4 / -1 voor de laatste trede, en waarom werkt het hier ook?
  Dit betekent van lijn 4 tot de laatste gridlijn. Bij vier kolommen is de laatste lijn lijn 5, waardoor de laatste trede in de vierde kolom terechtkomt.

## 5. Dierenasiel Zonnehoek
- Hoeveel layoutcontainers telt deze pagina, en welk gereedschap koos je voor elk?
  De pagina gebruikt meerdere layoutcontainers. Body gebruikt grid, header gebruikt flexbox, de navigatie gebruikt flexbox, het kaartenoverzicht gebruikt grid en elke kaart gebruikt flexbox in kolomrichting.

- Verklein het venster tot de helft: wat breekt er, en in welk hoofdstuk wordt dat opgelost?
  De kolommen worden te smal en de tekst breekt af. Dit wordt opgelost met responsieve grids en media queries in hoofdstuk 6.

## Thuis: B4.1

Geen modeloplossing: je site is van jou. Waar je zelf op controleert: `body` als grid `auto 1fr auto` met `min-height: 100vh`; de navigatie als flex-rij met `gap`; een kaartenrooster in grid met `fr` en `gap`; elke kaart een flex-column met `flex: 1` op de tekst; een commentaarregel per container met zijn taak; nergens `float`, `position` of `inline-block` voor een rij.
