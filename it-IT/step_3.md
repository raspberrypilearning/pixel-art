## Crea una griglia di pixel

Creiamo una griglia di pixel che potrai usare per creare pixel art.

La griglia sarà simile a una tabella. Le tabelle contengono righe, e le righe contengono le celle che rappresenteranno i pixel.

+ Apri [questo link per iniziare](http://jumpto.cc/web-pixel).

Il progetto dovrebbe assomigliare a questo:

![screenshot](images/pixel-starter.png)

Per prima cosa, scriviamo del codice per creare una tabella con uno sfondo nero e inseriamoci dei pixel bianchi.

+ Aggiungi questo codice nel `<body>` del tuo file `index.html` per creare un `<div>`:

![screenshot](images/pixel-art-art.png)

Un `<div>` è un box invisibile a cui puoi assegnare uno **style**. Questo `<div>` ha l'ID `art`, di cui hai bisogno per poter aggiungere stili al box.

+ Ora vai sul tuo file `Style.css` e aggiungi lo stile della tabella per il `<div>` chiamato `art`.

![screenshot](images/pixel-art-style.png)

Questo crea una tabella con un bordo e imposta la spaziatura all'interno della griglia.

Non sembra ancora molto bella esteticamente, è quindi necessario inserire righe di pixel al suo interno.

+ Torna al tuo file `index.html` e aggiungi una riga di tre pixel **all'interno** dell'`art` box. Se vuoi risparmiare tempo, puoi scrivere la prima riga e poi copiarla e incollarla per crearne altre.

![screenshot](images/pixel-art-row.png)

Nota che qui stai usando una **classe** invece di un ID per lo stile dei div. Questo perché ce ne saranno molti, quindi una classe è più utile.

+ Passa al file `style.css` e aggiungi i seguenti stili per le righe e i pixel all'interno di ogni riga:

![screenshot](images/pixel-art-row-style.png)

Ora i tuoi pixel si allineano in una griglia con linee nere attorno a loro.

+ Nel tuo file `index.html`, aggiungi altre due sezioni di pixel per creare una griglia di pixel 3 × 3. Puoi copiare e incollare di nuovo per risparmiare tempo.

\--- hints \---

\--- hint \---

Find the `<div>` tag with the class `row` and copy it, including the three rows labelled `pixel` which are inside it, up to and including its matching `</div>` tag.

Paste this code immediately below the section you just copied to create another row. Repeat once more so that you have three rows of three pixels each.

You can check whether your table looks right by looking at the result area on the right.

\--- /hint \---

\--- hint \---

Here is how your code should look:

![screenshot](images/pixel-art-grid-3.png)

\--- /hint \---

\--- /hints \---