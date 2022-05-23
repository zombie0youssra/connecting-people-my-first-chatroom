<!-- Topics: opdrachtgever-naam, semester-naam, sprint-naam, niveau-naam -->

# My first chatroom

In deze deeltaak i) zet je een voorbeeld van een chatroom live op je eigen heroku omgeving en ii) vertaal je de algemeen opgemaakte chatroom naar de huisstijl van jouw opdrachtgever.

## Context

Deze leertaak hoort bij sprint 11 "Connecting People". Dit is een deeltaak die je individueel uitvoert.

## Doel van deze opdracht

Je leert in deze deeltaak kleine aanpassingen te maken aan een realtime webapp. Daarna leer je de huisstijl van een opdrachtgever toe te passen op deze webapp. Als je tijd over hebt zijn er een aantal uitdagingen, je voegt dan functionaliteit toe aan de chatroom die je als basis krijgt.

## Werkwijze

Opdracht: de huisstijl van een opdrachtgever implementeren op een bestaande chatroom.

Deze opdracht gaat over alle fases van de DLC  [bouwen](#bouwen), [integreren](#integreren)

### Bouwen
*In de bouwfase realiseer je de beslissingen uit de ontwerpfase.*

<details>
<summary>Aanpak</summary>

1. Zet een Express omgeving op en deel bestanden via de ```./public/``` (optioneel) of gebruik EJS voor templating.
2. Implementeer jouw eerste chatroom op dusdanige wijze dat deze geserveerd wordt door Express.
3. Zet socket.io op. Maak een basic real-time chatroom welke gebruik maakt van sockets. Minimaal kan een client een bericht sturen welke een *round-trip* maakt naar de clients.
4. Set-up socket.io. Create a basic real-time app using sockets. Je kunt het voorbeeld uit de les gebruiken voor inspiratie!
5. (Optioneel) Voeg extra functionaliteit van onderstaande lijst toe. Doe dit een stapje tegelijk, zoek naar voorbeelden en vraag hulp als je dat nodig hebt.
	- Voeg support toe voor het kiezen van een *nickname*.
	- Stuur een bericht rond als iemand *connect* of *disconnect*
	- Voeg *{gebruiker} is aan het typen* functionaliteit toe
	- Laat zien wie er online is
	- Voeg *private messaging* toe

#### Materiaal bouwfase

- [Express](https://expressjs.com/en/4x/api.html)
- [socket.io](https://socket.io/)
- [live coded example](https://github.com/ju5tu5/barebonechat)
- [chat demo from socket.io](https://socket.io/get-started/chat/)

</details>

### Integreren
*In de integratiefase voer je de aanpassingen door zodat iedereen ze kan zien.*

<details>
<summary>Aanpak</summary>

1. Zorg dat je jouw app *deployed* via Heroku. Je kunt dit op twee manieren doen, via het verbinden van jouw GitHub repository of, moeilijker, via de command line interface (CLI).
2. Voeg aan jouw ```Readme.md``` een link naar je live-demo en een screenshot toe. Beschrijf ook welke extra functionaliteit je toegevoegd hebt.

#### Materiaal integratiefase

- [Heroku](https://www.heroku.com/)
- [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)
- [Resource](https://example.com)

</details>

## Criteria
*Definitions of done*

Focus sprint 11 - De focus van deze sprint ligt op het maken van multi-user omgeving door het opzetten van een real-time verbinding tussen client en server. 

### Deze leertaak hoort bij het gedragscriterium:

P: Je combineert aangeboden principes en conventies op het gebied van frontend, interface design en vormgeving om een passende oplossing voor een opdrachtgever te realiseren.
L: Je maakt aangeboden en zelf gevonden materie eigen en gebruikt dit bij leertaken, deelt ervaring binnen de squad.

Deze opdracht is done als:

[ ] - De chatroom staat live op heroku en is opgemaakt volgens de huisstijl van een opdrachtgever.
