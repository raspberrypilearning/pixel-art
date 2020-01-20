## Izradite rešetku piksela

Napravimo rešetku piksela koje možete koristiti za stvaranje piksela.

Rešetka će izgledati poput stola. Tablice sadrže retke, a redovi sadrže ćelije koje predstavljaju piksele.

+ Otvorite [starter triketu](http://jumpto.cc/web-pixel).

Projekt bi trebao izgledati ovako:

![screenshot](images/pixel-starter.png)

Prvo napišite neki kôd da biste izradili tablicu s crnom pozadinom i stavili bijele piksele u nju.

+ Dodajte ovaj kôd u `<body>` svoje `index.html` datoteke za stvaranje `<div>`:

![screenshot](images/pixel-art-art.png)

`<div>` je nevidljivi okvir na koji možete dati **stil**. Ovaj `<div>` ima ID `art`, koji vam je potreban kako biste u okvir dodali stilove.

+ Sada idite na `style.css` datoteku i dodajte stil stola za `<div>` zove `art`.

![screenshot](images/pixel-art-style.png)

To stvara tablicu s granicom i postavlja razmak unutar rešetke.

Još ne izgleda zanimljivo, stoga trebate staviti redke piksela unutar nje.

+ Vratite se na `index.html` datoteku i dodajte redak od tri piksela **u** okvir `art`. Ako želite uštedjeti vrijeme, možete upisati prvi red, a zatim kopirati i zalijepiti da biste stvorili ostale.

![screenshot](images/pixel-art-row.png)

Primijetite da ovdje upotrebljavate **klase** umjesto ID-a za stilizaciju divova. To je zato što će ih biti puno, pa je klasa korisnija.

+ Prijeđite na `style.css` datoteku i dodajte sljedeće stilove za retke i piksele unutar svakog retka:

![screenshot](images/pixel-art-row-style.png)

Sada će vam se pikseli smjestiti u mrežu s crnim crtama oko njih.

+ U `index.html` datoteku dodajte još dva odjeljka piksela za izradu rešetke 3 × 3 piksela. Možete ponovno kopirati i zalijepiti da biste uštedjeli vrijeme.

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