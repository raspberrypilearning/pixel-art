## Färbe die Pixel

Dieses Projekt verwendet drei verschiedene Sprachen:

+ HTML wird verwendet, um die Inhalte zu organisieren
+ CSS teilt dem Inhalt, mit Stilen, mit wie er aussehen soll
+ JavaScript ist eine Programmiersprache, mit der du eine Webseite auf Interaktionen reagieren lassen kannst

Fügen wir einen JavaScript-Code hinzu, um die Farbe in einem Pixel automatisch zu ändern, wenn du darauf klickst.

Wir erstellen eine **Funktion** (engl.: function). Funktionen sind benannte Codeblöcke, die eine bestimmte Aufgabe ausführen. Wir können eine Funtion über ihren Namen **aufrufen**, wenn wir den Code ausführen wollen, den sie enthält.

+ In der Datei `script.js` erstellst du eine Funktion mit dem Namen `setPixelColour` ("setzePixelFarbe"). Die `setPixelColour` Funktion muss ein `pixel` als **Eingabe** bekommen, damit sie die Farbe dieses Pixels ändern kann.

![Eine Funktion erstellen](images/create-function.png)

+ Füge diesen Code in die Funktion ein, um die Hintergrundfarbe des Pixels festzulegen:

![Screenshot](images/pixel-art-set-pixel-colour.png)

Beachte, dass `backgroundColor` ("HintergrundFarbe") die amerikanische Schreibweise 'color' verwendet, statt der britischen 'colour'.

Momentan hat dieser Code noch keine Wirkung.

+ Wechsle zu `index.html` und füge dem ersten Pixel den folgenden Code hinzu, damit beim Klicken auf diesen Pixel die `setPixelColour` Funktion aufgerufen wird:

![Screenshot](images/pixel-art-onclick.png)

Das `this` ("dieser") in den Klammern ist die Eingabe für die `setPixelColour` Funktion, die angibt, für welchen Pixel die Farbe eingestellt werden soll - `this`("diesen") Pixel!

+ Teste den Code, durch klicken auf den ersten Pixel. Er sollte schwarz werden.

![Screenshot](images/pixel-art-black.png)

Du hast `onclick`-Code ur zum **ersten** Pixel hinzugefügt, also passiert bei einem Klick auf die anderen Pixel noch nichts.