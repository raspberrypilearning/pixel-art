## Creează o grilă de pixeli

Hai să creăm o grilă de pixeli pe care o poți folosi pentru a crea artă cu pixeli.

Grila va arăta ca și un tabel. Tabelul conține linii, iar liniile conțin celule care vor reprezenta pixelii.

+ Deschide [trinketul de început](http://jumpto.cc/web-pixel).

Proiectul ar trebui să arate astfel:

![captură de ecran](images/pixel-starter.png)

Mai întâi, hai să scriem niște cod pentru a crea un tabel cu un fundal negru și apoi să adaugăm niște pixeli albi în el.

+ Adaugă acest cod în secțiunea `<body>` a fișierului tău `index.html` pentru a crea un `<div>`:

![captură de ecran](images/pixel-art-art.png)

Un `<div>` este o casetă invizibilă pe care o poți **stiliza**. Acest `<div>` are ID-ul `art`, de care vei avea nevoie pentru a adăuga stiluri la casetă.

+ Acum, mergi la fișierul tău `style.css` și adaugă stilul tabelului pentru elementul `<div>` numit `art`.

![captură de ecran](images/pixel-art-style.png)

Acest lucru va crea un tabel cu un chenar și setează spațiere în interiorul grilei.

Nu arată foarte interesant încă, așa că trebuie să pui linii de pixeli în el.

+ Mergi înapoi la fișierul tău `index.html` și adaugă o linie cu 3 pixeli **în interiorul** casetei `art`. Dacă vrei să economisești timp, poți scrie prima linie și apoi să dai copy paste pentru a crea celalalte.

![captură de ecran](images/pixel-art-row.png)

Observă că aici folosești o **clasă** în loc de un ID pentru a stiliza elementele div. Acest lucru se datorează faptului că vor fi mai multe, așa că o clasă este mult mai utilă.

+ Comută la fișierul `style.css` și adaugă următoarele stiluri pentru liniile și pixelii din fiecare linie:

![captură de ecran](images/pixel-art-row-style.png)

Acum, pixelii tăi să vor alinia într-o grilă cu linii negre în jurul lor.

+ În fișierul tău `index.html`, adaugă încă două secțiuni de pixeli pentru a crea o grilă 3x3 de pixeli. Poți să dai copy paste din nou pentru a economisi timp.

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