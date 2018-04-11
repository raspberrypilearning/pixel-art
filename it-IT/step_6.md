## Aggiungi una tavolozza di colori

Ti è seccato non poter modificare il colore di un pixel facendolo tornare bianco in caso di errore? Risolviamo subito il problema creando una tavolozza di colori in modo da poter fare clic su un colore per modificare la penna.

+ Per prima cosa, crea uno stile per la penna.

	Aggiungi la seguente sintassi in fondo al file `style.css`:

	![screenshot](images/pixel-art-pen.png)

+ Adesso, crea i colori bianco e nero per la penna che utilizzano quello stile.

	Aggiungi la seguente sintassi al file `index.html` dopo il tag `<body>`:

	![screenshot](images/pixel-art-palette.png)

	`style=` ti consente di aggiungere il CSS all’interno dell’HTML, opzione alquanto pratica in questo caso.

+ Desideriamo poter modificare il colore della penna quando si fa clic su un colore della tavolozza.

	Per memorizzare l’informazione, vengono utilizzate delle variabili. Creiamo la variabile penColour in `script.js`.

	Aggiungi la sintassi seguente in cima al file:

	![screenshot](images/pixel-art-pencolour.png)

	Aggiungi quindi una funzione per modificare la variabile penColour:

	![screenshot](images/pixel-art-set-pen.png)

+ Dovrai inoltre utilizzare il colore della penna quando cambi il colore di un pixel.

	Modifica la funzione `setPixelColour` in modo da utilizzare la variabile `penColour` invece di `black`:

	 ![screenshot](images/pixel-art-use-pen.png)

+ Adesso, dovrai richiamare la funzione `setPenColour` quando si fa clic su un colore della penna.

	Aggiungi la sintassi evidenziata `onclick` ai colori della penna:

	![screenshot](images/pixel-art-palette-onclick.png)

+ Verifica se riesci a cambiare il colore della penna da nero a bianco e viceversa per riempire o annullare un pixel.
