## Colora i pixel

Questo progetto utilizza tre diversi linguaggi:

+ HTML è usato per organizzare i tuoi contenuti
+ CSS dice al contenuto come apparire con gli stili
+ JavaScript è un linguaggio di programmazione che può essere utilizzato per modificare una pagina Web durante l’interazione con la stessa

Andrai ad aggiungere codice JavaScript per colorare automaticamente i pixel quanto ci clicchi sopra.

Creeremo una **funzione**. Le funzioni sono blocchi di codice che eseguono un'attività particolare. Possiamo **chiamare** una funzione con il suo nome quando vogliamo eseguire il codice che contiene.

+ All'interno del file `script.js` crea una funzione con il nome `setPixelColour`. La funzione `setPixelColour` ha bisogno di prendere un `pixel` come **input** in modo che possa cambiare il colore di quel pixel.

![Crea la funzione](images/create-function.png)

+ Aggiungi questo codice all'interno della funzione per impostare il colore di sfondo dei pixel:

![screenshot](images/pixel-art-set-pixel-colour.png)

Si noti che ` backgroundColor ` usa l'ortografia americana di "colore".

Al momento questo codice non ha alcun effetto.

+ Vai al `index.html` e aggiungi il seguente codice al primo pixel in modo che quando clicchi su questo pixel, la funzione `setPixelColour` sia chiamata:

![screenshot](images/pixel-art-onclick.png)

Il `questo` nelle parentesi è l'input per la funzione `setPixelColour` che permette di sapere su quale pixel impostare il colore per — `questo` pixel!

+ Metti alla prova il tuo codice facendo clic sul primo pixel. Dovrebbe diventare nero.

![screenshot](images/pixel-art-black.png)

Hai aggiunto solo il codice ` onclick ` per il ** primo ** pixel, quindi se clicchi sugli altri pixel ci sarà nessun cambiamento.