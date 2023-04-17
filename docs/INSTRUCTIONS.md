
# Look and Feel - Living Styleguide

Ontwerp en maak een *living styleguide* voor een opdrachtgever.

## Context

Deze deeltaak hoort bij sprint 4 Look and Feel. Dit is een deeltaak die je in een team uitvoert, namelijk alle studenten die een project voor dezelfde opdrachtgever doen.

In de workshop Living Styleguide wordt uitgelegd wat een living styleguide is en wat het nut ervan is.


## Doel van deze opdracht

> Living style guides are an important tool for web development today, especially in large, complex web applications. They help document styles and patterns, keep designers and developers in sync, and greatly help to organize and distill complex interfaces. (<cite>[Lambert, 2016](https://www.smashingmagazine.com/2016/05/creating-a-living-style-guide-case-study/))

Een living styleguide is essentieel voor het begrijpen en overbrengen van de look and feel van een website. Het geeft een gedeeld begrip van alle teamleden over hoe iets eruit moet zien en hoe markup (HTML) en vormgeving (CSS) moeten worden toegepast. Een living styleguide helpt bij het ontwerpen en bouwen van een website met consistente look and feel in de huisstijl van een opdrachtgever.

## Werkwijze

Deze opdracht gaat over [analyseren](#analyseren) en [ontwerpen](#ontwerpen) van de DLC. In de analysefase breng je door het doen van een *interface audit* in kaart hoe het zit met de consistentie van de huidige uitingen van de opdrachtgever en welke huisstijl elementen in gebruik zijn. Het resultaat is een *interface inventory*. In de ontwerpfase maak je keuzes, bepaal je ontwerp standaarden en leg je vast hoe componenten in HTML en CSS opgenomen worden. 

Het resultaat is een levende - dat wil zeggen live, semantisch, toegankelijk en responsive - stijlgids welke gebruikt kan worden door alle frontenders in een organisatie. Welke kleuren en typografie worden gebruikt in de huisstijl? Wat zijn overeenkomstige elementen van de verschillende pagina's of componenten? Hoe ziet de layout van verschillende onderdelen eruit? Hoe gedraagt de website zich in verschillende contexten (responsive design). En tenslotte, welke HTML en CSS is nodig om de elementen van de living styleguide op te maken en vorm te geven?

### Analyseren

Je begint met het uitvoeren van een *interface audit* waarin je een gecategoriseerde opsomming maakt van de componenten waaruit jouw website, app, intranet, hatseflats of whatever opgebouwd is. Het resultaat van de audit is een *interface inventory*, een verzameling van alle atomen, moleculen en organismen van een interface.

Een *interface inventory* is een goed middel om een opdrachtgever of werkgever over te halen om extra tijd uit te trekken voor het vastleggen van een solide ontwerpsysteem. Het maken van een living-styleguide is een goed idee voor het consistent toepassen van een huisstijl, maar het kost wel tijd om er een te ontwikkelen. Het laten zien van inconsistentie door middel van een interface inventory kan overtuigend werken.

**N.B: Jullie voeren de interface audit uit op alle gemaakte projecten voor de opdrachtgever. Dus kies de oorspronkelijke huisstijl én alle uitgewerkte user-stories!**

#### Voer een interface audit uit:
 
 1. **Open het project.** Zorg dat je weet hoe je specifieke screenshots moet maken (een selectie en niet je hele scherm).
 2. **Zet een blanco template op.** Hier dump en categoriseer je de componenten van de interface. Doe dit bij voorkeur in de wiki van de deeltaak. Alles wat je nodig hebt zijn een categorie titel en een plek om screenshots te dumpen.
 3. **Begin met screenshotten.** Nu het leuke gedeelte. Neem screenshots van de ingrediënten van jouw interface. Je doel is om unieke versies van componenten te vangen. Hier een mogelijke categorisering (kies wat van toepassing is op jouw project!):
    - Globals: header, footer en andere globale elementen
    - Navigatie: primair, footer, paginering, kruimelpad, …
    - Afbeeldingen: logo’s, hero’s, avatars, thumbnails, …
    - Iconen: vergrootglas, sociale, spinners, favicons, hamburgers, pijlen, …
    - Formulieren: inputs, textareas, select menu’s, checkboxes, radio buttons, …
    - Knoppen: groot, klein, primair, secundair, voortgang, …
    - Interactieve componenten: accordions, tabs, carrousels, alles met bewegende delen
    - Media: video spelers, audio spelers, …
    - Berichtgeving: alerts, success, error, warning, validatie, …
    - Headings: h1, h2, h3, h4, h5, h6 en typografische variaties
    - Lijsten: ongeordend, geordend, definitielijst, bullets, lijnen, …
    - 3de partij: widgets, iframes, beurs-tickets, social links, alles wat niet op hetzelfde domein gehost wordt
    - Reclame: reclame banners en andere reclame elementen
    - Blokken: combinaties van afbeeldingen, koppen en inleidingen, …
    - Animatie: gifjes van interface animatie of echt werkende animaties
    - Kleuren: unieke huisstijlkleuren
    - …
4. **Categoriseer jouw screenshots.** Je kunt dit doen terwijl je bezig bent of na afloop van je screenshot sessie. Het doel is dat je alle verschillende voorkomens van een bepaald molecuul naast elkaar kunt zien.
5. **Presenteer.** Laat als groep de interface inventory zien aan je ~~opdrachtgever~~ docent en kijk toe hoe ze in tranen uitbarsten. Na deze exercitie ga je door met [ontwerpen](#ontwerpen).

#### Meer lezen?

- [Brad Frost, Interface Inventory, 2013](https://bradfrost.com/blog/post/interface-inventory/)
- [Laure Gabrielle Chatenet, Ousama Jaâfour, How to create an interface inventory? 2017](https://capian.co/blog/interface-inventory/)
- [Mar High, How to create an interface inventory, 2021](https://mainmatter.com/blog/2021/06/02/how-to-create-an-interface-inventory/)
- [Brad Frost, Atomic Design, 2013](https://bradfrost.com/blog/post/atomic-web-design/)

### Ontwerpen

Je hebt inmiddels vast een beeld bij wat een huisstijl is. De meeste opdrachtgevers van FDND-Agency maken gebruik van een of andere styleguide waarin de huisstijl vastgelegd is. Bekijk als voorbeeld de [huisstijl van de Hogeschool van Amsterdam](https://www.hva.nl/praktisch/algemeen/hva-breed/communicatie/hva-huisstijl/hva-huisstijl.html). Een groot nadeel van traditionele huisstijlhandboeken is dat ze meestal in de vorm van een PDF gemaakt worden. De reden daarvoor is dat ontwerpers dit van oudsher zo gewend zijn te doen. Voor een toegankelijk ontwerp in een responsive omgeving is dit echter niet genoeg. Frontenders willen weten hoe een logo zich gedraagt als er weinig ruimte, een beetje meer ruimte én veel of zelfs heel veel ruimte is. Kortom, we hebben behoefte aan een responsive variant op het klassieke huisstijlhandboek.

Een *living styleguide* of levende stijlgids biedt het antwoord op de tragisch statische handboeken van weleer. De *living styleguide* is een modern huisstijlhandboek welke in de browser leeft, het is een website over websites van een organisatie. *Living* heeft hierbij een dubbele betekenis. Enerzijds is het een live, toegankelijke en semantische verzameling huisstijlcomponenten. Anderzijds is het een up-to-date huisstijl welke bijgehouden wordt als ontwerpbeslissingen genomen worden, dus *living* in de zin van groei.

Goede voorbeelden van een levende stijlgids zijn de [Decathlon Design System](https://www.decathlon.design/726f8c765/p/75e137-digital-overview) of de  [Familysearch Styleguide](https://www.familysearch.org/frontier/styleguide/) uit een artikel van Steven Lambert op Smashing Magazine. Het artikel staat onderaan bij ‘Meer lezen?’ mocht je het willen lezen.

**N.B: Jullie maken één living styleguide per opdrachtgever. Het is aan te raden teamleden als member toe te voegen op één repository en daar in samen te werken. Als het project af is kan je die repository forken om het project op te nemen in je eigen portfolio.**

#### Maak een living styleguide
Alhoewel bedrijven vaak aandacht besteden aan het uiterlijk van de living styleguide gaat het in dit geval écht om de inhoud. Richt je dus in eerste instantie daar op. In deze repository is een voorbeeldstructuur opgenomen maar deze mag je naar eigen inzicht volledig aanpassen.

1. **Kies een categorie** uit de interface inventory en onderzoek of je overeenkomsten kunt ontdekken.  Als je met een team werkt kan je categorieën verdelen. Het is aan te raden in verschillende bestanden te werken.
2. **Schrijf HTML**. Kies de best passende elementen en neem die met nette, toegankelijke en semantische HTML op in het betreffende bestand.  Blijf zo dicht mogelijk bij het origineel van de opdrachtgever (dus gebruik de originele huisstijl).
3. **Schrijf CSS**. Schrijf CSS voor de zojuist opgenomen elementen. Zorg dat 
4. **Maak een voorbeeld** voor frontenders die deze *living styleguide* gebruiken. Het handigste is om dit tussen `<pre>` en `<code>` tags te doen zoals in het onderstaande voorbeeld:\
```
<pre>
<code>
  <h1>Heading Level 1</h1>
</code>
</pre>
```
5. **Schrijf uitleg** over hoe de elementen wel en niet gebruikt mogen worden.
6. **Ga terug naar 1**. Je gaat door tot alle nodige elementen in de *living styleguide* zijn opgenomen.

#### Meer lezen?

- [Steven Lambert, Creating A Living Style Guide, 2016](https://www.smashingmagazine.com/2016/05/creating-a-living-style-guide-case-study/)

## Criteria

Focus sprint 4 - De focus van deze sprint ligt op het toepassen van een huisstijl en het maken van formulieren.

Deze deeltaak hoort bij het gedragscriterium:  

Samenwerken: Draagt verantwoording voor eigen resultaten en verwerkt ontvangen feedback.

Deze opdracht is done als:

- [ ] een Interface Inventory is opgenomen in de wiki
- [ ] een living styleguide is gemaakt met HTML en CSS
- [ ] de living styleguide te bekijken is via Github pages

