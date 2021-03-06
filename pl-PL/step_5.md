## Pokoloruj piksele

Ten projekt wykorzystuje trzy różne języki:

+ HTML służy do porządkowania treści
+ CSS mówi treści, jak wyglądać ze stylami
+ JavaScript to język programowania, którego można użyć, aby strona internetowa reagowała podczas interakcji z nią

Dodajmy trochę kodu JavaScript, aby pokolorować piksel automatycznie po kliknięciu.

Stworzymy **funkcję**. Funkcje to nazwane bloki kodu, które wykonują określone zadanie. Możemy **wywoływać** funkcję używając jej nazwy, gdy chcemy uruchomić kod, który zawiera.

+ Wewnątrz pliku `script.js` utwórz funkcję o nazwie `setPixelColour`. Funkcja `setPixelColour` musi przyjąć `piksel` jako **argument**, aby mogła zmienić kolor tego piksela.

![Stwórz funkcję](images/create-function.png)

+ Dodaj ten kod wewnątrz funkcji, aby ustawić kolor tła piksela:

![zrzut ekranu](images/pixel-art-set-pixel-colour.png)

Zauważ, że `backgroundColor` używa amerykańskiej pisowni słowa "colour".

W tej chwili ten kod nie ma żadnego efektu.

+ Przejdź do `index.html` i dodaj następujący kod do pierwszego piksela, aby po kliknięciu tego piksela została wywołana funkcja `setPixelColour`:

![zrzut ekranu](images/pixel-art-onclick.png)

`this` (z ang. ten) w nawiasach jest argumentem dla funkcji `setPixelColour`, pozwalającym określić, któremu pikselowi należy ustawić kolor - `temu` pikselowi!

+ Przetestuj swój kod, klikając na pierwszy piksel. Powinien stać się czarny.

![zrzut ekranu](images/pixel-art-black.png)

Dodałeś kod `onclick` tylko do **pierwszego** piksela, więc kliknięcie innych pikseli niczego jeszcze nie zrobi.