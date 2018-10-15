## Oboji piksele

U ovom projektu koriste se tri različita jezika:

+ HTML se koristi za organizovanje sadržaja
+ CSS određuje izgled sadržaja pomoću stilova
+ JavaScript je programski jezik koji možeš da koristiš da napraviš da veb-stranica reaguje u tvojoj interakciji sa njom

Dodajmo Javascript kôd da se piksel automatski oboji kada klikneš na njega.

Kreiraćemo **funkciju**. Funkcije su imenovani blokovi kôda koji izvršavaju određeni zadatak. Možemo **pozvati** funkciju navodeći njen naziv kada želimo da izvršimo kôd koji ona sadrži.

+ Unutar `script.js` datoteke kreiraj funkciju sa nazivom `setPixelColour`. Funkcija `setPixelColour` treba da ima `pixel` kao **ulaz** kako bi mogla da promijeni boju piksela.

![Napravi funkciju](images/create-function.png)

+ Dodaj ovaj kôd unutar funkcije da postaviš boju pozadine piksela:

![screenshot](images/pixel-art-set-pixel-colour.png)

Primijeti da se u `backgroundColor` koristi američki pravopis za 'colour' (boja).

Trenutno ovaj kôd nema nikakav učinak.

+ Idi u `index.html` i dodaj sljedeći kôd prvom pikselu tako da funkcija `setPixelColour` bude pozvana kada klikneš na taj piksel:

![screenshot](images/pixel-art-onclick.png)

Riječ `this` u zagradama je ulaz za funkciju `setPixelColour` i ona omogućava funkciji da prepozna kojem pikselu treba da postavi boju — `this` pixel (ovaj piksel)!

+ Isprobaj svoj kôd tako što ćeš kliknuti na prvi piksel. Trebalo bi da postane crn.

![screenshot](images/pixel-art-black.png)

Kôd `onclick` dodali smo samo **prvom** pikselu, tako da se još uvijek neće ništa desiti kada klikneš na druge piksele.