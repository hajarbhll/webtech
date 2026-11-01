# Labo 3 - reflecties

Naam: Hajar Bahloul 

## 1. Kleurenstalen

- Welke twee waarden uit de user agent stylesheet moest je op de lijst wegwerken, en waar las je ze af?

Ik moest de bolletjes van de lijst en de insprong van de lijst verwijderen. Ik zag deze waarden in het boxmodel en in de browser.

- Wat verandert er aan de banden als je het venster hoger maakt, en wat verandert er niet?

De banden worden hoger omdat ze 50vh gebruiken. De kleuren, de tekst en de breedte blijven hetzelfde.

## 2. Slogan

- Welke property centreerde de tekst, en welke de kolom?

De tekst werd gecentreerd met text-align: center. De kolom werd gecentreerd met margin: auto.

- Waarom werkte de padding op de knop pas na `display: inline-block`?

Omdat een gewone link een inline-element is. Met display: inline-block reageert de knop correct op padding.

## 3. Tabblad

- Wat is de visuele breedte van het tabblad, en waarom is dat exact 15rem en geen 15rem plus padding plus border?

Door box-sizing: border-box worden padding en border meegeteld in de opgegeven breedte. Daarom blijft de visuele breedte exact 15rem.

## 4. Donut

- Waarom werkt `height: 70%` op de cirkel, terwijl F3.2 zegt dat een procentuele hoogte meestal niets doet?

Omdat de ouder een vaste hoogte heeft. Daardoor kan de browser 70% van die hoogte berekenen.

- Tegen welke maat van de ouder rekende de browser `margin: 15%`: de breedte of de hoogte?

De browser berekende die marge ten opzichte van de breedte van de ouder.

## 5. Landingspagina

- Gaf je `main` een `height` of een `min-height`, en waarom?

Ik gebruikte min-height zodat de hero-sectie minstens 80% van de vensterhoogte vult maar nog kan meegroeien als er meer inhoud is.

- Wat gebeurt er met de twee helften als je een regeleinde zet tussen `</article>` en `<div class="afbeelding">`?

Dan ontstaat er extra witruimte tussen de twee inline-block elementen waardoor de uitlijning verandert.

## Thuis: B3.1 (met AI of zonder AI)

Welke route koos je? Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1. Ik heb de kleuren aangepast zodat ze overeenkwamen met het voorbeeld.
2.k heb de afmetingen van het tabblad aangepast om beter aan te sluiten bij het screenshot. 
3. k heb de hoogte van de hero-sectie aangepast met min-height in plaats van height.
