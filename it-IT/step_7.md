## Aggiungi una tavolozza di colori

Hai trovato fastidioso non poter cambiare il colore di un pixel in bianco in caso di errore? Risolviamo subito il problema creando una tavolozza di colori in modo da poter fare clic su un colore per modificare la penna.

+ Aggiungi il seguente codice in fondo al file `style.css` per creare uno stile per la penna:

![screenshot](images/pixel-art-pen.png)

+ Ora crea una tavolozza con i colori della penna in bianco e nero usando lo stile di penna appena creato. Aggiungi il seguente codice al tuo ` index.html` sotto il tag `<body>`:

![screenshot](images/pixel-art-palette.png)

` style = ` ti permette di aggiungere codice CSS all'interno del tuo file HTML, opzione alquanto pratica in questo caso.

Dobbiamo aggiungere il codice in modo che quando uno dei colori della tavolozza viene cliccato, il colore della penna cambi.

+ Passa a `script.js` e crea una variabile chiamata `penColour` in cima al file. Imposta il valore della variabile a `'black'`.

[[[generic-javascript-create-variable]]]

\--- hints \--- \--- hint \--- Aggiungi il seguente codice all'inizio del file:

![screenshot](images/pixel-art-pencolour.png) \--- /hint \--- \--- /hints \---

+ Sotto la variabile, crea una nuova funzione chiamata `setPenColour` con un input di `pen`. Guarda la funzione `setPixelColour` che hai già creato per aiutarti.

[[[generic-javascript-create-a-function]]]

+ All'interno della funzione `setPenColour` aggiungi il codice per impostare la variabile `penColour` al colore `pen` fornito come input.

![screenshot](images/pixel-art-set-pen.png)

Avrai anche bisogno di usare la variabile ` penColour ` quando cambi il colore di un pixel.

+ Cambia la funzione `setPixelColour` per utilizzare la variabile `penColour` invece di `nero`:
    
    ![screenshot](images/pixel-art-use-pen.png)

+ Nel file `index.html` aggiungi un codice per chiamare la funzione `setPenColour` quando viene cliccato un colore nella tavolozza.

![screenshot](images/pixel-art-palette-onclick.png)

+ Verifica di poter cambiare il colore della penna tra bianco e nero per inserire o eliminare i pixel.