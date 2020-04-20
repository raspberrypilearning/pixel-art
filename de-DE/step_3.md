## Erstelle ein Pixelraster

Lass uns ein Pixelraster erstellen, mit dem du Pixelbilder erstellen kannst.

Das Raster wird wie eine Tabelle aussehen. Tabellen enthalten Zeilen und Zeilen enthalten Zellen, die die Pixel darstellen.

+ Öffne das [Starter Trinket](http://jumpto.cc/web-pixel).

Das Projekt sollte so aussehen:

![screenshot](images/pixel-starter.png)

Zuerst schreiben wir einen Code, um eine Tabelle mit schwarzem Hintergrund zu erstellen und dann weiße Pixel einzufügen.

+ Füge diesen Code in den `<body>` (Körper) deiner `index.html` Datei ein, um ein `<div>` zu erstellen:

![Screenshot](images/pixel-art-art.png)

Eine `<div>` ist ein unsichtbares Feld, dem du einen **Stil** (engl.: style) zuweisen kannst. Diese `<div>` hat die ID `art` (Kunst), die du benötigst, damit du Stile zum Feld hinzufügen kannst.

+ Gehe nun zu deiner `style.css` Datei und füge den Tabellenstil für die `art` genannte `<div>` hinzu.

![Screenshot](images/pixel-art-style.png)

Dadurch wird eine Tabelle mit einem Rand erstellt und der Abstand innerhalb des Rasters gesetzt.

Es sieht noch nicht sehr interessant aus, daher musst du die Zeilen der Pixel darin platzieren.

+ Gehe zurück zu deiner `index.html ` Datei und füge eine Zeile (engl.: row) mit drei Pixeln **in** die `art` Box ein. Wenn du Zeit sparen möchtest, kannst du die erste Zeile eingeben und dann kopieren und einfügen, um die anderen Zeilen zu erstellen.

![Screenshot](images/pixel-art-row.png)

Beachte, dass Du hier hier eine **Klasse** (engl.: class) anstelle einer ID verwendest, um die Divs zu gestalten. Das ist so, weil es viele davon geben wird, sodass eine Klasse nützlicher ist.

+ Wechsel in die Datei `style.css` und füge die folgenden Stile für die Zeilen und die Pixel in jeder Zeile hinzu:

![Screenshot](images/pixel-art-row-style.png)

Jetzt werden deine Pixel in einem Raster mit schwarzen Linien um sie herum ausgerichtet.

+ In deiner `index.html` Datei füge weitere zwei Teile von Pixeln hinzu, um ein 3×3 Pixel-Raster zu erstellen. Du kannst erneut kopieren und einfügen benutzen, um Zeit zu sparen.

\--- hints \---

\--- hint \---

Finde den `<div>`Tag</0> mit der Klasse `row` und kopiere ihn, einschließlich der drei Zeilen, die mit `pixel` gekennzeichnet sind, einschließlich des zugehörigen `</div>` Tags.

Füge diesen Code direkt unterhalb des Abschnitts ein, den du gerade kopiert hast, um eine neue Zeile zu erstellen. Wiederhole dies erneut, damit du drei Zeilen von jeweils drei Pixeln hast.

Du kannst überprüfen ob deine Tabelle richtig aussieht, indem du dir die Ergebnisseite rechts anschaust.

\--- /hint \---

\--- hint \---

Here is how your code should look:

![screenshot](images/pixel-art-grid-3.png)

\--- /hint \---

\--- /hints \---