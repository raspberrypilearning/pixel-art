## Füge eine Farbpalette hinzu

Findest du es nervig, dass du eine Pixel-Farbe nicht wieder zu weiß verwandeln kannst, wenn du einen Fehler gemacht hast? Lass uns dieses Problem beheben, indem wir eine Farbpalette erstellen, damit du auf eine Farbe klicken kannst, um die Stiftfarbe zu ändern. 

+ Lass uns als erstes den Stiftstil erstellen. 

	Füge den folgenden Code unten in deiner `style.css` Datei hinzu:

	![screenshot](images/pixel-art-pen.png)

+ Erstelle jetzt schwarze und weiße Stiftfarben, die diesen Stil benutzen. 

	Füge den folgenden Code zum `index.html` (Inhaltsverzeichnis) nach dem `<body>` (Hauptteil) hinzu:

	![screenshot](images/pixel-art-palette.png)

	`style=` Stil ermöglicht dir, den CSS Code in deinem HTML hinzuzufügen, was sehr bequem und einfach ist. 

+ Du willst in der Lage sein, die Stiftfarbe zu ändern, wenn die Farbpalette angeklickt wird. 

	Die Variablen werden benutzt, um Informationen zu speichern. Lass uns eine Stiftfarben-Variable in `script.js` erstellen.

	Füge den folgenden Code oben in der Datei hinzu:

	![screenshot](images/pixel-art-pencolour.png)

	Füge dann eine Funktion hinzu, um die Stiftfarbe zu ändern:

	![screenshot](images/pixel-art-set-pen.png)

+ Du wirst auch die Stiftfarbe benutzen müssen, wenn du die Farbe eines Pixels ändern willst. 

	Ändere die `setPixelColour` (Pixel-Farbe einstellen) Funktion, um die `penColour` (Stiftfarbe) Variable anstelle von `black` (schwarz) zu benutzen:

	 ![screenshot](images/pixel-art-use-pen.png)

+ Jetzt musst du die `setPenColour` (Stiftfarbe einstellen) Funktion aufrufen, wenn die Stiftfarbe angeklickt wird. 

	Füge den markierten `onclick` Code zu deinen Stiftfarben hinzu:

	![screenshot](images/pixel-art-palette-onclick.png)

+ Teste jetzt, ob du die Stiftfarbe zwischen schwarz und weiß wechseln kannst, um die Pixel auszumalen oder zu löschen.
