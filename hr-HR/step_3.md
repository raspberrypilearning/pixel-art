## Izradite rešetku piksela

Napravimo rešetku piksela koje možete koristiti za stvaranje piksela.

Rešetka će izgledati poput stola. Tablice sadrže retke, a redovi sadrže ćelije koje predstavljaju piksele.

+ Otvorite [starter triketu](http://jumpto.cc/web-pixel).

Projekt bi trebao izgledati ovako:

![zaslona](images/pixel-starter.png)

Prvo napišite neki kôd da biste izradili tablicu s crnom pozadinom i stavili bijele piksele u nju.

+ Dodajte ovaj kôd u `<body>` svoje `index.html` datoteke za stvaranje `<div>`:

![zaslona](images/pixel-art-art.png)

`<div>` je nevidljivi okvir na koji možete dati **stil**. Ovaj `<div>` ima ID `art`, koji vam je potreban kako biste u okvir dodali stilove.

+ Sada idite na `style.css` datoteku i dodajte stil stola za `<div>` zove `art`.

![zaslona](images/pixel-art-style.png)

To stvara tablicu s granicom i postavlja razmak unutar rešetke.

Još ne izgleda zanimljivo, stoga trebate staviti redke piksela unutar nje.

+ Vratite se na `index.html` datoteku i dodajte redak od tri piksela **u** okvir `art`. Ako želite uštedjeti vrijeme, možete upisati prvi red, a zatim kopirati i zalijepiti da biste stvorili ostale.

![zaslona](images/pixel-art-row.png)

Primijetite da ovdje upotrebljavate **klase** umjesto ID-a za stilizaciju divova. To je zato što će ih biti puno, pa je klasa korisnija.

+ Prijeđite na `style.css` datoteku i dodajte sljedeće stilove za retke i piksele unutar svakog retka:

![zaslona](images/pixel-art-row-style.png)

Sada će vam se pikseli smjestiti u mrežu s crnim crtama oko njih.

+ U `index.html` datoteku dodajte još dva odjeljka piksela za izradu rešetke 3 × 3 piksela. Možete ponovno kopirati i zalijepiti da biste uštedjeli vrijeme.

\--- savjeti \--- \--- savjet \--- Pronađite `<div>` oznaku sa 123</code> redkom `klase i kopirajte ga, uključujući tri redaka označena <code>piksela` koja su u njemu, do i uključujući njezin odgovarajući `</div>` oznaka.

Zalijepite ovaj kôd odmah ispod dijela koji ste upravo kopirali da biste izradili drugi redak. Ponovite još jednom, tako da imate tri reda po tri piksela svaki.

Možete provjeriti izgleda li tablica ispravno gledanjem područja rezultata s desne strane. \--- / savjet \--- \--- savjet \--- Evo kako treba izgledati vaš kôd:

![zaslona](images/pixel-art-grid-3.png) \--- / savjet \--- \--- / savjeti \---