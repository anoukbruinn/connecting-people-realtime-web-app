> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Titel
<!-- Geef je project een titel en schrijf in één zin wat het is -->

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Gebruik](#gebruik)
  * [Kenmerken](#kenmerken)
  * [Installatie](#installatie)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
<!-- Bij Beschrijving staat kort beschreven wat voor project het is en wat je hebt gemaakt -->

Ik heb bij de website voor Buurtcampus oost een online chat. 
<!-- Voeg een mooie poster visual toe 📸 -->

Hieronder is het knopje rechtsonder te zien waar je op moet klikken zodat de pop up uitgevoerd word.
<img width="373" alt="Scherm­afbeelding 2023-06-14 om 12 03 19" src="https://github.com/anoukbruinn/connecting-people-realtime-web-app/assets/112856687/a55184c9-d401-413e-a1f1-e23e60be4fa0">

Hieronder zie je hoe het eruit ziet als er op de knop is gedrukt. (dit is de mobile version)

<img width="373" alt="Scherm­afbeelding 2023-06-14 om 12 03 37" src="https://github.com/anoukbruinn/connecting-people-realtime-web-app/assets/112856687/eb3b6607-a1f3-4db8-bed2-8b983bcf93eb">


<!-- Voeg een link toe naar Github Pages 🌐-->

## Gebruik
<!-- Bij Gebruik staat de user story, hoe het werkt en wat je er mee kan. -->

De userstorie van deze opdracht: de userstorie die ik heb hiervoor is. 

Ik wil een chat kunnen versturen via een pop up op de website. 

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met JS gedaan en hoe? Misschien heb je iets met NodeJS gedaan, of heb je een framwork of library gebruikt? -->

Hiervoor is gewerkt met 


* javascript
  
```js
// Luister naar berichten van de server
ioServer.on('message', (message) => {
  loadingState.style.display = 'none'
  emptyState.style.display = 'none'
  addMessage(message) 

```
  
* css

```css

.chatbox-wrapper {
  position: sticky;
  bottom: 0;
  height: 60px;
}

```

* html

```html

<%- include('./partials/chatbot.ejs') %>

 ```

* .ejs

```ejs

 <!-- State messages -->
    <span class="loading">Berichten aan het inladen...</span>
    <span class="empty">Er zijn nog geen berichten hier, typ iets om te kijken of er iemand reageert.</span>
    <!-- <span class="offline">Er gaat iets mis met de verbinding, we proberen de connectie te herstellen...</span> -->

    <ul></ul>

```

## Installatie
<!-- Bij Instalatie staat hoe een andere developer aan jouw repo kan werken -->



## Bronnen

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
