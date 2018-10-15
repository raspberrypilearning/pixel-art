## Napravi rešetku od piksela

Napravimo rešetku od piksela koju možeš da koristiš za kreiranje pixel art-a.

Rešetka će izgledati kao tabela. Tabele sadrže redove, a redovi sadrže ćelije koje će predstavljati piksele.

+ Otvori [početni trinket](http://jumpto.cc/web-pixel).

Projekat treba da izgleda ovako:

![screenshot](images/pixel-starter.png)

Prvo napišimo kôd kako bismo napravili tabelu sa crnom pozadinom i u nju stavili bijele piksele.

+ Dodaj ovaj kôd u `<body>` svoje `index.html` datoteke da kreiraš `<div>`:

![screenshot](images/pixel-art-art.png)

Elemenat `<div>` je nevidljiva kutija kojoj možeš da dodijeliš **stil**. Ovaj `<div>` ima ID `art` koji ti je potreban za dodavanje stilova kutiji.

+ Sada pređi na svoju `style.css` datoteku i dodaj stil tabele za `<div>` sa nazivom `art`.

![screenshot](images/pixel-art-style.png)

Tako kreiraš tabelu sa okvirom i podešavaš razmak unutar rešetke.

Još uvijek ne izgleda zanimljivo, pa stoga treba da postaviš redove piksela unutar nje.

+ Vrati se na svoju `index.html` datoteku i dodaj red od tri piksela **unutar** kutije `art`. Ako želiš da uštediš vrijeme, možeš upisati prvi red, a zatim ga kopirati i prenijeti da napraviš ostale.

![screenshot](images/pixel-art-row.png)

Obrati pažnju na to da ovdje za stilizovanje elemenata div upotrebljavaš **class** umjesto ID-a. Razlog za to je što će ih biti mnogo, pa je klasa korisnija.

+ Pređi na `style.css` datoteku i dodaj sljedeće stilove za redove i piksele unutar svakog reda:

![screenshot](images/pixel-art-row-style.png)

Sada će se tvoji pikseli poređati u rešetku sa crnim linijama oko njih.

+ U svoju `index.html` datoteku dodaj još dva reda piksela da kreiraš rešetku od 3x3 piksela. Možeš ponovo koristiti kopiranje i prenošenje da uštediš vrijeme.

\--- hints \--- \--- hint \--- Nađi oznaku `<div>` sa klasom `row` i kopiraj je, uključujući tri reda označena sa `pixel` koja su unutar nje, kao i odgovarajuću završnu oznaku `</div>`.

Prenesi ovaj kôd odmah ispod dijela koji si upravo kopirao/kopirala da kreiraš drugi red. Ponovi to još jednom, tako da imaš tri reda po tri piksela.

Možeš da provjeriš da li tvoja tabela izgleda ispravno tako što ćeš pogledati rezultat sa desne strane. \--- /hint \--- \--- hint \--- Tvoj kôd treba da izgleda ovako:

![screenshot](images/pixel-art-grid-3.png) \--- /hint \--- \--- /hints \---