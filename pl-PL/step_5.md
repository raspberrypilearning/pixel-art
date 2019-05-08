## Pokoloruj piksele

Ten projekt wykorzystuje trzy różne języki:

+ HTML służy do porządkowania treści
+ CSS mówi zawartość, jak wyglądać ze stylami
+ JavaScript jest językiem programowania, za pomocą którego strona internetowa może reagować na interakcję z nią

Dodajmy trochę kodu JavaScript, aby kolorować w pikselach automatycznie po kliknięciu.

Stworzymy **funkcję**. Funkcje są nazwane blokami kodu, które wykonują określone zadanie. Możemy **wywoływać** funkcję według jej nazwy, gdy chcemy uruchomić kod, który zawiera.

+ Wewnątrz pliku `script.js` utwórz funkcję o nazwie `setPixelColour`. Funkcja `setPixelColour` musi przyjąć `piksel` jako **wejście** , aby mógł zmienić kolor tego piksela.

![Utwórz funkcję](images/create-function.png)

+ Dodaj ten kod do funkcji, aby ustawić kolor tła piksela:

![zrzut ekranu](images/pixel-art-set-pixel-colour.png)

Zauważ, że `backgroundColor` używa amerykańskiej pisowni "color".

W tej chwili ten kod nie ma żadnego efektu.

+ Przejdź do `index.html` i dodaj następujący kod do pierwszego piksela, aby po kliknięciu tego piksela została wywołana funkcja `setPixelColour`:

![zrzut ekranu](images/pixel-art-onclick.png)

`to` w nawiasach jest wejściem dla funkcji `setPixelColour` , która pozwala mu określić, który piksel ma ustawić kolor dla - `tego` piksela!

+ Przetestuj swój kod, klikając pierwszy piksel. Powinno stać się czarne.

![zrzut ekranu](images/pixel-art-black.png)

Dodałeś tylko `kod onclick` do **pierwszego** piksela, więc kliknięcie innych pikseli nic jeszcze nie da.