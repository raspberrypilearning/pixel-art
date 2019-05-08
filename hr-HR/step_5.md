## U boji piksela

Ovaj projekt koristi tri različita jezika:

+ HTML se koristi za organiziranje sadržaja
+ CSS govori sadržaju kako izgledati stilom
+ JavaScript je programski jezik koji možete koristiti za izradu web stranice kada reagirate s njom

Dodajte neki JavaScript kôd koji će se automatski bojati u pikselu kada kliknete na njega.

Izradit ćemo **funkciju**. Funkcije se nazivaju blokovi koda koji izvršavaju određeni zadatak. Možemo **nazvati** funkciju po imenu kada želimo pokrenuti kôd koji sadrži.

+ Unutar `script.js` datoteku stvorite funkciju s imenom `setPixelColour`. `funkcija setPixelColour` treba uzeti `piksel` kao unos **** kako bi promijenio boju tog piksela.

![Izradi funkciju](images/create-function.png)

+ Dodajte ovaj kôd unutar funkcije da biste postavili boju pozadine piksela:

![screenshot](images/pixel-art-set-pixel-colour.png)

Napominjemo da `backgroundColor` koristi američki pravopis 'boja'.

Trenutačno ovaj kôd nema nikakav učinak.

+ Idite na `index.html` i dodajte sljedeći kôd prvom pikselu tako da kada kliknete na taj piksel, naziva se `setPixelColour` funkcija:

![screenshot](images/pixel-art-onclick.png)

`ovo` u zagradama je unos za `setPixelColour` funkciju koja omogućuje da znaju koji piksel postaviti boju za - `ovaj` piksel!

+ Isprobajte svoj kôd klikom na prvi piksel. Trebao bi postati crn.

![screenshot](images/pixel-art-black.png)

Dodali ste samo `onclick` kod **prvih** piksela, pa klikom na druge piksele još uvijek neće učiniti ništa.