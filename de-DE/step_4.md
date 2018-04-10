## Die Pixel färben

HTML wird benutzt, um den Inhalt zu organisieren und CSS wird benutzt, um den Inhalt grafisch zu gestalten. JavaScript ist eine Programmiersprache, die benutzt werden kann, um eine Webseite zu ändern, während man damit interagiert. 

Du könntest HTML und CSS benutzen, um die Hintergrundfarbe von einzelnen Pixeln einzustellen, aber das wäre ein sehr langwieriger Prozess! Statt dessen wirst du JavaScript Code hinzufügen, um deine Pixel automatisch zu färben, bzw. bunt zu gestalten, wenn du auf sie klickst. 

+ In JavaScript wird der Code in eine `function` (Funktion) platziert, die aufgerufen werden kann, wenn wir diesen Code laufen lassen wollen. 

	Du wirst eine Funktion namens `setPixelColour` (Pixel-Farbe einstellen) erstellen

	Die `setPixelColour` (Pixel-Farbe einstellen) Funktion muss wissen, welche Pixel die Farbe ändern sollen, dies ist eine `input` (Eingabe).

	Füge den folgenden Code zur `script.js` Datei hinzu, um die Hintergrundfarbe eines Pixels einzustellen:

	![screenshot](images/pixel-art-set-pixel-colour.png)

	Hast du bemerkt, dass `backgroundColor` (Hintergrundfarbe) die amerikanische Buchstabierweise benutzt: „color“ statt Britisch Englisch „colour“? 

+ Wir müssen jetzt diese Funktion aufrufen, wenn ein Pixel angeklickt wird.

	HTML benutzt `onclick` (beim Anklicken), um eine Funktion aufzurufen, wenn ein Element angeklickt wird. Du wirst in 'this' (dieses) als die Eingabe daran vorbeigehen müssen, damit deine Funktion weiß, für welche Pixel es die Farbe ändern soll. 

	Gehe zum `index.html` (Inhaltsverzeichnis) und füge den folgenden Code zum ersten Pixel hinzu:

	![screenshot](images/pixel-art-onclick.png)

+ Teste deinen Code, indem du auf das erste Pixel klickst. Es sollte jetzt schwarz werden:

	![screenshot](images/pixel-art-black.png)

	Du hast den `onclick` (beim Anklicken) Code nur zum ersten Pixel hinzugefügt, dies wird also noch nicht bei den anderen Pixeln funktionieren. 
