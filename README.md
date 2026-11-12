# Learning Log

## 12 november 2026 | Sprint 0

### Oefening 1 font properties

<img src="./readme-images/cssoefening1.png" width="200" alt="CSS stap 1">
<small>Stap 1: De bestanden openen
Als eerste heb ik de bestanden gedownload en geopend in VSCodium. Voordat ik kon beginnen, moest ik alleen nog uitzoeken hoe ik mijn resultaat als webpagina kon bekijken. Ik wilde namelijk niet steeds tussen mijn code en een browser wisselen. Daarom ben ik gaan kijken hoe ik met Live Preview mijn aanpassingen direct kon zien.</small>

<img src="./readme-images/cssoefening2.png" width="200" alt="CSS stap 2">
<small>Stap 2: Het normale lettertype toevoegen
De eerste uitdaging was het toevoegen van Expletus Sans. Hiervoor moest ik @font-face gebruiken, iets waar ik nog niet eerder mee had gewerkt. Het was even zoeken hoe ik het lettertypebestand op de juiste manier kon koppelen. Uiteindelijk werd duidelijk dat ik hiervoor de naam, de locatie van het bestand en de letterdikte moest aangeven.</small>

<img src="./readme-images/cssoefening3.png" width="200" alt="CSS stap 3">
<small>Stap 3: Het vetgedrukte lettertype toevoegen
Vervolgens ging ik aan de slag met de vetgedrukte versie van Expletus Sans. Hierbij maakte ik meteen een fout: ik had alleen de vetgedrukte variant toegevoegd en de normale versie overgeslagen.
Wat ik eerst niet begreep, was waarom ik twee keer @font-face nodig had. Beide bestanden horen tenslotte bij hetzelfde lettertype. Later ontdekte ik dat je hiermee aangeeft welke variant de browser moet gebruiken bij normale of vetgedrukte tekst.</small>

<img src="./readme-images/cssoefening4.png" width="200" alt="CSS stap 4">
<small>Stap 4: Het lettertype toepassen
Nu beide varianten waren toegevoegd, dacht ik dat het lettertype automatisch zichtbaar zou zijn. Dat bleek niet zo te werken.
Met font-family moest ik nog aangeven dat de tekst in het hoofdgedeelte van de pagina Expletus Sans moest gebruiken. Hierdoor begreep ik het verschil tussen een lettertype beschikbaar maken en het daadwerkelijk toepassen op een element.</small>

<img src="./readme-images/cssoefening5.png" width="200" alt="CSS stap 5">
<small>Stap 5: De tekst vormgeven
Daarna kon ik beginnen met het aanpassen van de tekst zelf. Ik experimenteerde met de lettergrootte, letterdikte, kleur en regelafstand.
Dit ging niet meteen goed. Zo had ik een letterdikte van 500 ingesteld, terwijl ik alleen de varianten 400 en 700 had toegevoegd. Daarnaast werd mijn hele alinea roze, terwijl dat niet de bedoeling was. Ik heb de tekst daarom weer zwart gemaakt.
Door deze aanpassingen zag ik steeds beter welk effect de verschillende CSS-properties hadden. Vooral het verschil tussen de eigenschappen en de waarden die je eraan geeft, werd duidelijker.</small>

<img src="./readme-images/cssoefening6.png" width="200" alt="CSS stap 6">
<small>Stap 6: De eerste letter aanpassen
De laatste stap was het vormgeven van de eerste letter van de alinea. Met ::first-letter kon ik specifiek die ene letter selecteren.
Vervolgens heb ik deze groter en vetgedrukt gemaakt en de dieproze kleur uit de opdracht toegepast. Dit onderdeel vond ik interessant, omdat ik niet wist dat je met CSS zo gericht één letter kon aanpassen.

Hierna heb ik gecontroleerd of alle gevraagde eigenschappen in mijn CSS stonden en het resultaat vergeleken met het voorbeeld.</small>

### Reflectie

Deze oefening kostte me meer moeite dan ik vooraf had verwacht. Ik merk dat ik CSS nog behoorlijk ingewikkeld vind, vooral omdat er zoveel verschillende properties en waarden zijn.
In het begin was ik voornamelijk bezig met het invullen van de juiste code. Ik had daarbij regelmatig uitleg nodig, omdat ik niet altijd begreep waarom iets op een bepaalde manier moest.
Wat me hielp, was om de opdracht op te delen in kleine stappen. Hierdoor kon ik steeds één onderdeel aanpassen en bekijken wat er op mijn webpagina veranderde.
Daarnaast begrijp ik nu beter hoe je met CSS heel specifieke onderdelen van een tekst kunt vormgeven. Hoewel ik de opdracht uiteindelijk heb kunnen uitvoeren, zou ik dit nog niet helemaal zelfstandig kunnen. Ik wil daarom meer oefenen met CSS, zodat ik niet alleen weet welke code ik nodig heb, maar ook begrijp hoe ik daar zelf op kan komen.

### 1. Praktische CSS Voorbereiding

<img src="./readme-images/stap1.png" width="200" alt="Stap 1">
<small>Stap 1: De basisstructuur
Ik ben begonnen met het maken van een HTML-pagina in CodePen. Hiervoor heb ik een hoofdtitel en een korte introductie toegevoegd.</small>

<img src="./readme-images/stap2.png" width="200" alt="Stap 2">
<small>Stap 2: Een tussenkopje toevoegen
Vervolgens heb ik een tussenkopje toegevoegd om mijn pagina meer structuur te geven.</small>

<img src="./readme-images/stap3.png" width="200" alt="Stap 3">
<small>Stap 3: Alinea’s toevoegen
Daarna heb ik twee alinea’s toegevoegd waarin ik uitleg wat een Digital Garden is en wat ik ermee wil doen.</small>

<img src="./readme-images/stap4.png" width="200" alt="Stap 4">
<small>Stap 4: Een afbeelding toevoegen
Ik heb een afbeelding toegevoegd via een online link en daarbij een passende beschrijving geschreven.</small>

<img src="./readme-images/stap5.png" width="200" alt="Stap 5">
<small>Stap 5: Een opsomming maken
Vervolgens heb ik een opsomming gemaakt van vier onderwerpen die ik in mijn Digital Garden wil verzamelen.</small>

<img src="./readme-images/stap6.png" width="200" alt="Stap 6">
<small>Stap 6: Een citaat en afsluiting toevoegen
Als laatste heb ik een citaat toegevoegd en mijn pagina afgesloten met een laatste alinea.</small>

<img src="./readme-images/stap7.png" width="200" alt="Stap 7">
<small>
Stap 7: De HTML controleren
Ik heb gecontroleerd of alle onderdelen in de juiste volgorde stonden en of mijn pagina goed werd weergegeven.</small>

<img src="./readme-images/stap8.png" width="200" alt="Stap 8">
<small>
Stap 8: Het eindresultaat
Als laatste heb ik het eindresultaat bekeken. Mijn pagina heeft nu een duidelijke structuur, maar nog geen vormgeving. Die ga ik in de volgende opdracht toevoegen.</small>

### 2. Een lelijke pagina leesbaar maken

<img src="./readme-images/step1.png" width="200" alt="Stap 1">
<small>Stap 1: De tekstbreedte aanpassen
Ik heb de maximale breedte van mijn pagina aangepast en de inhoud gecentreerd. Hierdoor worden de tekstregels korter en is de tekst makkelijker te lezen.</small>

<img src="./readme-images/step2.png" width="200" alt="Stap 2">
<small>Stap 1: De tekstbreedte aanpassen
Ik heb de maximale breedte van mijn pagina aangepast en de inhoud gecentreerd. Hierdoor worden de tekstregels korter en is de tekst makkelijker te lezen.</small>

<img src="./readme-images/step3.png" width="200" alt="Stap 3">
<small>Stap 3: Alinea’s toevoegen
Daarna heb ik twee alinea’s toegevoegd waarin ik uitleg wat een Digital Garden is en wat ik ermee wil doen.</small>

<img src="./readme-images/step4.png" width="200" alt="Stap 4">
<small>Stap 4: De cursor aanpassen
Ik heb een aanpassing gedaan waardoor de muisaanwijzer verandert in een handje wanneer je over een knop beweegt. Dit is nog niet zichtbaar, omdat mijn pagina geen knoppen bevat.</small>

<img src="./readme-images/step5.png" width="200" alt="Stap 5"> 
<small>Stap 5: Het lettertype van invoervelden aanpassen
Vervolgens heb ik ervoor gezorgd dat knoppen en invoervelden hetzelfde lettertype gebruiken als de rest van mijn pagina. Ook dit is nog niet zichtbaar, omdat ik deze onderdelen nog niet heb toegevoegd.</small>

<img src="./readme-images/step6.png" width="200" alt="Stap 6">
<small>Stap 6: Het eindresultaat controleren
Als laatste heb ik gecontroleerd of alle aanpassingen goed werkten. Mijn pagina is nu overzichtelijker en beter leesbaar dan bij de eerste opdracht.</small>

### CSS Diner game

<img src="./readme-images/flukeout1.png" width="200" alt="Stap 1"> <img src="./readme-images/flukeout2.png" width="200" alt="Stap 2">
<img src="./readme-images/flukeout3.png" width="200" alt="Stap 3"> <img src="./readme-images/flukeout4.png" width="200" alt="Stap 4">

#### CSS Diner

Tijdens deze oefening heb ik CSS Diner gespeeld om te leren hoe CSS-selectors werken. Met verschillende opdrachten moest ik bijvoorbeeld appels, borden en bentobakjes selecteren. Hierbij heb ik geleerd hoe je elementen kunt selecteren met hun naam, een class of een ID, en hoe je meerdere selectors kunt combineren.
Ik vond deze opdracht best lastig, omdat ik in het begin eigenlijk geen idee had wat ik aan het doen was. Ik wist vaak niet waarom ik iets moest invullen en wat de verschillende tekens betekenden. Daardoor was ik vooral bezig met het vinden van het juiste antwoord, in plaats van begrijpen hoe het werkte. Toen ik meer uitleg kreeg over de verschillende selectors, begon ik het langzaam beter te begrijpen. Ik merk wel dat ik hier nog mee moet oefenen om het zelfstandig te kunnen toepassen.

## 11 november 2026 | Sprint 0

### Schetsen van o.a. interactie en animatie

#### Schets oefeningen:

<img src="./readme-images/strepen.png" width="100" alt="Oefening 1"> <small>Oefening om rechten lijnen te tekenen.</small>

<img src="./readme-images/Vierkanten.png" width="100" alt="Oefening 2"> <small>Oefening om rechten vierkanten te tekenen.</small>

<img src="./readme-images/Telefoon.png" width="100" alt="Oefening 3"> <small>Oefening om je telefoon in ware grote te schetsen.</small>

#### Oefening rangschikken:

<img src="./readme-images/Schetsenvan1tm10.png" width="200" alt="Gezamelijke opdracht"> 
<small>Schetsen van Heleen rangschikken.</small>

#### mi-fi schets:

<img src="./readme-images/Websiteschets.png" width="100" alt="Opdracht 2"> <small>Een mi-fi schets</small>

#### Animaties schetsen:

<img src="./readme-images/Uitlegschets.png" width="200" alt="Uitleg animatie schets"> <img src="./readme-images/Animatieschets.png" width="300" alt="Uitleg animatie schets">

#### Wat heb ik gedaan?

Tijdens deze les heb ik verschillende schetsoefeningen gedaan. We begonnen met het tekenen van rechte lijnen en vierkanten. Daarna moesten we een telefoon op ware grootte schetsen.
Vervolgens gingen we kijken naar verschillende schetstechnieken en hoe je een schets duidelijker en overzichtelijker kunt maken. Hiervoor kregen we verschillende schetsen van Heleen die we moesten rangschikken van minder goed naar beter. We keken hierbij naar het gebruik van kleuren, annotaties, stippellijnen, schaduwen en highlights.
Daarna moesten we deze technieken zelf toepassen door een mi-fi-schets te maken van een website die we regelmatig gebruiken. Ik heb hiervoor de website van HEMA gekozen. Eerst heb ik de basis met een zwarte fineliner getekend en daarna heb ik met kleuren annotaties toegevoegd om bepaalde onderdelen duidelijker te maken.
Als laatste hebben we geoefend met het schetsen van animaties. Eerst kregen we uitleg van een docent over hoe je een animatie met schetsen kunt uitwerken. Vervolgens heb ik geprobeerd om dit zelf toe te passen.

#### Wat heb ik geleerd?

Ik heb geleerd dat schetsen niet alleen gaat om hoe mooi je kunt tekenen, maar vooral om hoe duidelijk je een idee kunt overbrengen. Door de verschillende schetsen te rangschikken, zag ik hoeveel verschil kleine toevoegingen kunnen maken. Denk bijvoorbeeld aan het gebruik van kleuren, schaduwen, annotaties en stippellijnen. Hierdoor wordt een schets veel makkelijker te begrijpen.
Ook heb ik geleerd hoe je een bestaande website kunt omzetten naar een mi-fi-schets en hoe je met verschillende technieken bepaalde onderdelen kunt benadrukken. Daarnaast heb ik kennisgemaakt met het schetsen van animaties en hoe je beweging kunt laten zien in een stilstaande tekening.

#### Wat had ik hiervoor nodig?

Voor deze oefeningen heb ik papier, een potlood, een zwarte fineliner en verschillende kleuren gebruikt. Daarnaast hebben we uitleg en voorbeelden gekregen van de docent over verschillende schetstechnieken en het schetsen van animaties.
Voor de mi-fi-schets heb ik de website van HEMA als voorbeeld gebruikt. Ook hebben de schetsen van Heleen mij geholpen om te herkennen welke technieken een schets duidelijker maken.

### Interactie: MMD, micro-interacties, forms

#### Inspiratie van andere forms:

<img src="./readme-images/voorbeeld1.png" width="100" alt="Inspiratie foto van pinterest"> <img src="./readme-images/voorbeeld2.png" width="200" alt="Inspiratie foto van pinterest"> <img src="./readme-images/voorbeeld3.png" width="100" alt="Inspiratie foto van pinterest"> <img src="./readme-images/voorbeeld4.png" width="200" alt="Inspiratie foto van pinterest"> <img src="./readme-images/voorbeeld5.png" width="100" alt="Inspiratie foto van pinterest"> <img src="./readme-images/voorbeeld5.png" width="100" alt="Inspiratie foto van pinterest"> <img src="./readme-images/voorbeeld6.png" width="100" alt="Inspiratie foto van pinterest">
<small>Bron: Pinterest, oorspronkelijke links onbekend.</small>

#### Eigen geschetste form:

<img src="./readme-images/Opdracht1form.png" width="200" alt="Antwoorden op de vragen">
<img src="./readme-images/geschetsteform.png" width="300" alt="Schets opdracht 1">

#### Wat heb ik gedaan?

Voor deze opdracht moest ik een bruikbaar online formulier ontwerpen voor Wok to Walk, waarbij gebruikers zelf hun maaltijd kunnen samenstellen. Ik ben begonnen met het verzamelen van inspiratie van verschillende menukaarten en formulieren. Hierbij heb ik vooral gekeken naar hoe de informatie werd verdeeld en hoe de vormgeving ervoor zorgde dat een menu overzichtelijk bleef.
Daarna heb ik nagedacht over de context en wat de gebruiker precies moet kunnen doen. Ik heb ervoor gekozen om het formulier op te delen in drie stappen: eerst een basis kiezen, vervolgens maximaal vier ingrediënten toevoegen en als laatste een saus kiezen. Vervolgens heb ik twee verschillende schetsen gemaakt om te onderzoeken hoe ik deze informatie het beste kon indelen.

#### Wat heb ik geleerd?

Ik heb geleerd dat het bij het ontwerpen van een formulier niet alleen gaat om hoe het eruitziet, maar vooral om hoe duidelijk het is voor de gebruiker. Je moet goed nadenken over de volgorde waarin iemand keuzes maakt en hoe je ervoor zorgt dat de gebruiker begrijpt wat er van diegene wordt verwacht.

#### Wat had ik hiervoor nodig?

Voor deze opdracht heb ik gebruikgemaakt van Pinterest om inspiratie te verzamelen van verschillende menukaarten en formulieren. Daarnaast heb ik de theorie uit de les over interactie gebruikt, zoals affordance, feedforward, feedback, cues en prompts. Deze begrippen hielpen mij om na te denken over hoe een gebruiker door het formulier wordt begeleid.

## 10 november 2026 | Sprint 0

### Opdracht: Programma's installeren

<img src="./readme-images/Onderzoekstuctuurlearninglog1.png" width="250" alt="Screenshot van de GitHub-documentatie over Markdown-koppen"> <img src="./readme-images/HTMLtabelonderzoek 2.png" width="250" alt="Screenshot van de uitleg over HTML-tabellen"> <img src="./readme-images/IMGonderzoek 2.png" width="250" alt="Screenshot van de uitleg over het HTML-element img en de attributen src, width en alt"> <img src="./readme-images/Fotostuctuuronderzoek 2.png" width="250" alt="Screenshot van onderzoek naar het structureren van afbeeldingen in een README">

#### Wat heb ik gedaan?

Ik heb onderzocht hoe ik mijn Learning Log kon vormgeven in mijn README. Ik wilde graag een duidelijke structuur maken en afbeeldingen toevoegen om mijn proces visueel te laten zien. Hiervoor heb ik verschillende manieren onderzocht om afbeeldingen toe te voegen en naast elkaar te plaatsen. Vervolgens heb ik dit zelf uitgeprobeerd in VSCodium en gekeken wat voor mijn Learning Log het beste werkte.

#### Wat heb ik geleerd?

Wat ik vooral spannend vond, was dat we geen AI mochten gebruiken om onze code te schrijven. Dit vind ik lastig, omdat ik vaak eerst ergens in moet komen en iets visueel moet zien om het te begrijpen. Als ik bijvoorbeeld code zie die voor een website wordt gebruikt, vind ik het moeilijk om die kennis vervolgens om te zetten naar mijn eigen code. Maar ik denk dat dat juist de uitdaging is.

Het heeft mij daarom ook veel tijd gekost om mijn Learning Log vorm te geven. Toch heb ik met een beetje hulp van ChatGPT en door zelf onderzoek te doen, manieren gevonden om mijn afbeeldingen en teksten vorm te geven. De code die ik uiteindelijk heb gebruikt, begrijp ik goed. Ik weet wat de verschillende onderdelen doen en wat er gebeurt als ik iets aanpas. Ik denk dat dat uiteindelijk het belangrijkste is.

#### Wat had ik hiervoor nodig?

Voor dit onderzoek heb ik gebruikgemaakt van GitHub Docs en MDN Web Docs. Deze websites hielpen mij om meer te begrijpen over Markdown en HTML. Daarnaast heb ik VSCodium gebruikt om mijn code uit te proberen en ChatGPT om uitleg te krijgen bij onderdelen die ik lastig vond en om mijn spelling en grammatica te controleren.

#### Bronnen en hulpmiddelen

- GitHub Docs: Uitleg over Markdown en het toevoegen van afbeeldingen.
- MDN Web Docs, HTML-tabellen: Uitleg over het gebruik van, src, width en alt.
- MDN Web Docs, HTML-afbeeldingen: Uitleg over het gebruik van img, src, width en alt.
- ChatGPT: Hulp bij het begrijpen en structureren van mijn README, het plaatsen van afbeeldingen en het controleren van spelling en grammatica.

### Opdracht: Klein beginnen

<img src="./readme-images/OpdrachtKleinbeginnen.png" width="250" alt="Screenshot van de opdracht Klein beginnen"> <img src="./readme-images/Opdrachtkleinbeginnen2.png" width="250" alt="Opdracht klein beginnen, afbeelding 2">

#### Wat heb ik gedaan?

Voor deze opdracht heb ik een kleine aanpassing gedaan aan mijn Digital Garden. Ik heb mijn naam toegevoegd aan de homepage. Dit heb ik aangepast in VSCodium en vervolgens doorgestuurd naar GitHub. Alleen ging dit niet helemaal zoals verwacht. Mijn naam was namelijk wel zichtbaar in de code op GitHub, maar niet op mijn website. Daarom ben ik gaan onderzoeken waar dit aan lag.

#### Wat heb ik geleerd?

Ik heb geleerd dat wanneer je iets aanpast in je code, dit niet altijd meteen zichtbaar is op je website. In eerste instantie dacht ik dat ik iets verkeerd had gedaan, omdat mijn naam maar niet verscheen. Uiteindelijk bleek dat GitHub Pages de wijzigingen wel goed had gepubliceerd, maar dat Safari nog een oude versie van mijn website liet zien door de cache.

#### Wat had ik hiervoor nodig?

Voor deze opdracht heb ik VSCodium gebruikt om mijn naam toe te voegen aan de HTML. Daarnaast heb ik GitHub gebruikt om mijn wijzigingen op te slaan en GitHub Pages om mijn website te publiceren.

Toen mijn naam niet zichtbaar werd op mijn website, heb ik ChatGPT uitgelegd wat ik had aangepast en wat er niet werkte. Vervolgens heb ik stap voor stap de mogelijke oorzaken gecontroleerd. Eerst heb ik gekeken of mijn wijzigingen wel waren opgeslagen in VSCodium en of de aangepaste code zichtbaar was op GitHub. Daarna heb ik bij GitHub Actions gecontroleerd of mijn website succesvol was gepubliceerd. Hier zag ik dat de publicaties allemaal succesvol waren verlopen.

Omdat mijn naam nog steeds niet zichtbaar was, ben ik verder gaan zoeken. Uiteindelijk bleek dat Safari nog een oudere versie van mijn website liet zien door de cache. Nadat ik dit had opgelost, werd mijn naam wel zichtbaar. ChatGPT heb ik dus vooral gebruikt om mij te helpen bij het zoeken naar de oorzaak van het probleem. Door zelf alle stappen te controleren, begreep ik steeds beter hoe GitHub Pages werkt.

---

## 9 november 2026 | Sprint 0

### Opdracht: Zelftest

<img src="./readme-images/HWIVI%20Zelftest.png" width="250" alt="HWIVI Zelftest"> <img src="./readme-images/Experimenteren%20met%20interactie.png" width="250" alt="Zelftest experimenteren met interactie">

#### Wat heb ik gedaan?

Tijdens de kick-off moesten we een zelftest doen. In deze test stonden 38 vragen met daarin theorie die je in leerjaar 1 tijdens alle blokken hebt gehad. Met de twee vragen: 1. Of je de theorie herkent en weet wat je ermee moet doen en 2. Welke theorie je denkt te moeten gebruiken voor dit blok.

#### Wat heb ik geleerd?

Ik heb dit formulier al eerder moeten invullen bij blok 1 en toen wist ik eigenlijk minder dan nu. Na blok 1 was ik de theorie niet per se vergeten, maar kon ik het niet meer zo één, twee, drie voor de geest halen. Wel als ik een korte uitleg kreeg. Nu, bij blok 2, ging het al een stuk makkelijker. Ik merk alleen dat ik snel denk dat ik alle theorie nodig heb en daarom alles wil aankruisen. Achteraf bleek dat ik iets selectiever kan zijn in welke theorie ik denk nodig te hebben voor dit blok.

### Opdracht: Bespreek de vragen

**Vraag: Wat is een source hosting platform?**

**Antwoord:**

Ik heb voor GitHub gekozen, omdat dit vanuit mijn studie wordt aangeraden en omdat ik hier vorig jaar ook mee heb gewerkt.

**Vraag: Welke domeinnaam heb jij gekozen en hoe heb je die gekoppeld aan jouw pagina?**

**Antwoord:**

Ik heb gekozen voor de naam Feetjes Wereld. Dit omdat ik dit blok graag mijn creativiteit wil laten zien.

**Vraag: Hoe kan je aanpassingen aan jouw pagina maken en hoe zorg je ervoor dat die op het web gepubliceerd worden?**

**Antwoord:**

Ik kan aanpassingen maken in VSCodium. Vervolgens moet ik mijn wijzigingen opslaan, committen en pushen naar GitHub. Daarna worden ze via GitHub Pages gepubliceerd.

### Bronnen en hulpmiddelen

**Bronnen en hulpmiddelen:**
Bronnen en hulpmiddelen

- GitHub Docs: Uitleg over Markdown en het toevoegen van afbeeldingen.
- MDN Web Docs, HTML-tabellen: Uitleg over het gebruik van, src, width en alt.
- MDN Web Docs, HTML-afbeeldingen: Uitleg over het gebruik van img, src, width en alt.
- ChatGPT: Hulp bij het begrijpen en structureren van mijn README, het plaatsen van afbeeldingen en het controleren van spelling en grammatica.

**Afbeeldingen:**

- Pinterest bij sprint 0: Gebruikt voor visuele inspiratie. De oorspronkelijke links naar de afbeeldingen zijn niet meer beschikbaar.
