## Dodaj paletu boja

Da li ti je zasmetalo što boju piksela ne možeš da vratiš u bijelu kada napraviš grešku? Riješimo to kreiranjem palete boja, tako da možeš da odabereš boju olovke jednim klikom.

+ Dodaj sljedeći kôd na kraju svoje `style.css` datoteke da kreiraš stil olovke:

![screenshot](images/pixel-art-pen.png)

+ Sada kreiraj paletu sa crnom i bijelom bojom olovke koristeći stil olovke koji si upravo kreirao/kreirala. Dodaj sljedeći kôd u `index.html`, ispod oznake `<body>`:

![screenshot](images/pixel-art-palette.png)

`style=` nam omogućuje da dodamo CSS kôd unutar HTML datoteke, što nam ovdje odgovara.

Potrebno je da dodamo kôd kako bi se boja olovke mijenjala kada se klikne na jednu od boja iz palete.

+ Pređi na `script.js` i kreiraj promjenljivu pod nazivom `penColour` na samom vrhu datoteke. Promjenljivoj dodijeli vrijednost `'black'` (crna).

[[[generic-javascript-create-variable]]]

\--- hints \---

\--- hint \---

Add the following code at the top of the file:

![screenshot](images/pixel-art-pencolour.png)

\--- /hint \---

\--- /hints \---

+ Ispod promjenljive kreiraj novu funkciju pod nazivom `setPenColour` sa ulazom `pen` (olovka). Pogledaj već kreiranu funkciju `setPixelColour` ako ti treba pomoć.

[[[generic-javascript-create-a-function]]]

+ Unutar funkcije `setPenColour` dodaj kôd za postavljanje promjenljive `penColour` na boju `olovke` (pen) koja je data kao ulaz.

![screenshot](images/pixel-art-set-pen.png)

You'll also need to use the `penColour` variable when you change the colour of a pixel.

+ Izmijeni funkciju `setPixelColour` tako da koristi promjenljivu `penColour` umjesto `black`:
    
    ![screenshot](images/pixel-art-use-pen.png)

+ U `index.html` datoteku dodaj kôd za pozivanje funkcije `setPenColour` kada se klikne na boju u paleti.

![screenshot](images/pixel-art-palette-onclick.png)

+ Isprobaj da li možeš da mijenjaš boju olovke iz crne u bijelu i obratno, za brisanje ili bojenje piksela.