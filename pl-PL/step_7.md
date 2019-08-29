## Dodaj paletę kolorów

Czy irytujące jest to, że nie można zmienić koloru piksela na biały, jeśli popełnisz błąd? Naprawmy to, tworząc paletę kolorów, aby można było wybierać między kolorami pióra za pomocą kliknięcia.

+ Dodaj ten kod u dołu pliku `style.css` , aby utworzyć styl pióra:

![zrzut ekranu](images/pixel-art-pen.png)

+ Teraz utwórz paletę z czarno-białymi kolorami pióra, używając właśnie utworzonego stylu pióra. Dodaj następujący kod do `index.html` pod tagiem `<body>`:

![zrzut ekranu](images/pixel-art-palette.png)

`style =` umożliwia dodanie kodu CSS do pliku HTML, co jest wygodne tutaj.

Musimy dodać kod, aby po kliknięciu jednego z kolorów w palecie zmieniał się kolor pisaka.

+ Przejdź na `skrypt.js` i utwórz zmienną o nazwie `penColour` na samej górze pliku. Ustaw wartość zmiennej na `"czarny"`.

[[[generic-javascript-create-variable]]]

\--- wskazówki \--- \--- podpowiedź \--- Dodaj następujący kod u góry pliku:

![screenshot](images/pixel-art-pencolour.png) \--- /hint \--- \--- /hints \---

+ Poniżej zmiennej, utwórz nową funkcję o nazwie `setPenColour` z wejściem `pisaka`. Spójrz na funkcję `setPixelColour` , którą już utworzyłeś, aby ci pomóc.

[[[generic-javascript-create-a-function]]]

+ Wewnątrz funkcji `setPenColour` dodaj kod, aby ustawić `penColour` zmienną na kolor `długopis` podany jako dane wejściowe.

![zrzut ekranu](images/pixel-art-set-pen.png)

You'll also need to use the `penColour` variable when you change the colour of a pixel.

+ Zmień funkcję `setPixelColour` , aby używać `zmiennej penColour` zamiast `czarnej`:
    
    ![zrzut ekranu](images/pixel-art-use-pen.png)

+ W pliku `index.html` dodaj kod do wywołania funkcji `setPenColour` po kliknięciu koloru w palecie.

![zrzut ekranu](images/pixel-art-palette-onclick.png)

+ Sprawdź, czy możesz zmienić kolor pióra między czarnym i białym, aby wypełnić lub usunąć piksele.