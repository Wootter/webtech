# Labo 3 - reflecties

Naam: (jouw naam)

## 1. Kleurenstalen

- Welke twee waarden uit de user agent stylesheet moest je op de lijst wegwerken, en waar las je ze af?
	Ik moest Padding: 0; en list-style: none; doen om de begin padding weg te halen en de bolletjes van de lijst te verwijderen. Deze vondt ik in de syllabus en in de text bij de oefening.

- Wat verandert er aan de banden als je het venster hoger maakt, en wat verandert er niet?
	De grootte van de banden varieert omdat het met vh is, de text is met rem en veranderd niet.

## 2. Slogan

- Welke property centreerde de tekst, en welke de kolom?
    text-align: center: zorgen voor de text en margin: 12rem zorgt er voor dat de hele box centraal staat.
- Waarom werkte de padding op de knop pas na `display: inline-block`?
    Dit zorgt ervoor dat de type box of boxen wordt gekozen voor de gegenereerde elementen. Dan kunnen we ze aanspreken met padding.

## 3. Tabblad

- Wat is de  dat exact 15rem en geen 15rem plus padding plus border?visuele breedte van het tabblad, en waarom is
	De visuele breedte is exact 15rem, omdat `box-sizing: border-box` ervoor zorgt dat de opgegeven breedte de inhoud, padding en border samen omvat.

## 4. Donut

- Waarom werkt `height: 70%` op de cirkel, terwijl F3.2 zegt dat een procentuele hoogte meestal niets doet?
	De cirkel heeft een parent, dus de cirkel wordt 70% van de parent.
- Tegen welke maat van de ouder rekende de browser `margin: 15%`: de breedte of de hoogte?
	De browser rekende dit uit op basis van de breedte van de ouder. Ook verticale percentages voor `margin` worden berekend ten opzichte van de breedte van het bevattende blok.

## 5. Landingspagina

- Gaf je `main` een `height` of een `min-height`, en waarom?
	`min-height` omdat de hoogte ook hoger mag zijn maar niet kleiner.
- Wat gebeurt er met de twee helften als je een regeleinde zet tussen `</article>` en `<div class="afbeelding">`?
	Ze komen onder elkaar te staan.

## Thuis: B3.1 (met AI of zonder AI)

Welke route koos je? Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1. 
2. 
3. 
