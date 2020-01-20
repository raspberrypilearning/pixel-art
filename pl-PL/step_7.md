## Dodaj paletę kolorów

Czy denerwuje Cię to, że nie możesz zmienić koloru piksela z powrotem na biały, jeśli popełnisz błąd? Naprawmy to, tworząc paletę kolorów, aby można było wybierać między kolorami pióra za pomocą kliknięcia.

+ Dodaj ten kod u dołu swojego pliku `style.css`, aby utworzyć styl pióra:

![zrzut ekranu](images/pixel-art-pen.png)

+ Teraz utwórz paletę z czarnym i białym kolorem pióra, używając właśnie utworzonego stylu pióra. Dodaj następujący kod do `index.html` poniżej tagu `<body>`:

![zrzut ekranu](images/pixel-art-palette.png)

`style=` umożliwia dodanie kodu CSS wewnątrz pliku HTML, co jest tutaj wygodne.

Musimy dodać kod, aby po kliknięciu jednego z kolorów w palecie zmieniał się kolor pióra.

+ Przejdź do `script.js` i utwórz zmienną o nazwie `penColour` na samej górze pliku. Ustaw wartość zmiennej na `"black"`.

[[[generic-javascript-create-variable]]]

\--- hints \---

\--- hint \---

Add the following code at the top of the file:

![zrzut ekranu](images/pixel-art-pencolour.png)

\--- /hint \---

\--- /hints \---

+ Poniżej zmiennej, utwórz nową funkcję o nazwie `setPenColour` z argumentem `pen`. Spójrz na funkcję `setPixelColour`, którą już utworzyłeś, aby ci pomóc.

[[[generic-javascript-create-a-function]]]

+ Wewnątrz funkcji `setPenColour` dodaj kod, aby ustawić zmienną `penColour` na kolor `pen` podany jako argument.

![screenshot](images/pixel-art-set-pen.png)

You'll also need to use the `penColour` variable when you change the colour of a pixel.

+ Zmień funkcję `setPixelColour`, aby używała zmiennej `penColour` zamiast `black`:
    
    ![zrzut ekranu](images/pixel-art-use-pen.png)

+ W pliku `index.html` dodaj kod do wywołania funkcji `setPenColour` po kliknięciu koloru w palecie.

![screenshot](images/pixel-art-palette-onclick.png)

+ Sprawdź, czy możesz zmienić kolor pióra między czarnym i białym, aby wypełnić lub usunąć piksele.