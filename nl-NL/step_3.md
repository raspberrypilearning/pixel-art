## Maak een raster van pixels

Laten we een raster van pixels maken dat je kunt gebruiken voor het maken van pixelkunst.

Het raster ziet eruit als een tabel. Tabellen bevatten rijen en rijen bevatten cellen die de pixels voorstellen.

+ Open de [start trinket](http://jumpto.cc/web-pixel).

Het project zou er als volgt uit moeten zien:

![screenshot](images/pixel-starter.png)

Laten we eerst een code schrijven om een ​​tabel met een zwarte achtergrond te maken om er vervolgens witte pixels in te plaatsen.

+ Voeg deze code toe aan de `<body>` van je `index.html` bestand om een ​​ `<div>` aan te maken:

![screenshot](images/pixel-art-art.png)

Een `<div>` is een onzichtbare doos (Engels: box) die je een **style** (stijl) kunt geven. Deze `<div>` heeft de ID `art` (kunst), die je nodig hebt om een stijl (opmaak) aan de box te kunnen toevoegen.

+ Ga nu naar je `style.css` bestand en voeg de tabelstijl toe voor de `<div>` genaamd `art`.

![screenshot](images/pixel-art-style.png)

Hiermee maak je een tabel met een rand en geef je de afstanden in het raster.

Het ziet er nog niet erg interessant uit, dus moet je er rijen pixels in plaatsen.

+ Ga terug naar je `index.html` bestand en voeg een rij van drie pixels **in** de box `art` toe. Als je tijd wilt besparen, typ je de eerste rij en kopieer en plak je deze in de andere rijen.

![screenshot](images/pixel-art-row.png)

Merk op dat je hier een **class** gebruikt in plaats van een ID om de div's te stijlen. Dit komt omdat er veel van zullen zijn, dus een class is nuttiger.

+ Schakel over naar het `style.css` bestand en voeg de volgende stijlen toe voor de rijen en de pixels binnen elke rij:

![screenshot](images/pixel-art-row-style.png)

Nu zullen je pixels in een raster worden geplaatst met zwarte lijnen eromheen.

+ Voeg in je `index.html` -bestand nog twee secties pixels toe om een ​​raster van 3 × 3 pixels te maken. Je kunt opnieuw kopiëren en plakken om tijd te besparen.

--- hints --- --- hint --- Zoek de `<div>` tag met de `row` en kopieer die, inclusief de drie rijen met het label `pixel` die erin zitten, tot en met de bijbehorende `</div>` tag.

Plak deze code direct onder de sectie die je zojuist hebt gekopieerd om een ​​nieuwe rij te maken. Herhaal dit nog een keer zodat je drie rijen van elk drie pixels hebt.

Je kunt controleren of je tabel er goed uitziet door naar het resultaat aan de rechterkant te kijken. --- / hint --- --- hint --- Zo zou je code eruit moeten zien:

![screenshot](images/pixel-art-grid-3.png) --- /hint --- --- /hints ---