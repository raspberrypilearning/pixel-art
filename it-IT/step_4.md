## Colora i pixel

Il codice HTML viene impiegato per organizzare il contenuto, mentre il CSS per attribuirgli uno stile. JavaScript è un linguaggio di programmazione che può essere utilizzato per modificare una pagina Web durante l’interazione con la stessa.

Puoi utilizzare l’HTML e il CSS per impostare il colore di sfondo di pixel individuali, ma ci vorrebbe molto tempo! Andrai invece ad aggiungere codice JavaScript per colorare automaticamente i pixel quanto ci clicchi sopra.

+ In JavaScript, il codice viene posizionato in un tag `function` che può essere richiamato quando desideriamo eseguire tale codice.

	Creerai ora una funzione chiamata `setPixelColour`

	La funzione `setPixelColour` deve sapere di quale pixel modificare il colore. Tale istruzione si chiama `input`.

	Aggiungi il seguente codice al file `script.js` per impostare il colore di sfondo di un pixel:

	![screenshot](images/pixel-art-set-pixel-colour.png)

	`backgroundColor` utilizza la lingua inglese con ortografia americana.

+ Dobbiamo ora richiamare quella funzione in modo che si attivi quando si fa clic su un pixel.

	L’HTML utilizza l’evento `onclick` per richiamare una funzione quando si fa clic su un elemento. Dovrai rendere "this" l’input in modo che la funzione sappia di quale pixel modificare il colore.

	Vai a `index.html` e aggiungi la seguente sintassi al primo pixel:

	![screenshot](images/pixel-art-onclick.png)

+ Verifica la sintassi facendo clic sul primo pixel. Dovrebbe diventare di colore nero:

	![screenshot](images/pixel-art-black.png)

	Hai aggiunto la sintassi `onclick` solamente al primo pixel; non funzionerà quindi ancora con gli altri pixel.
