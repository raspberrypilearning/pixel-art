## Utwórz siatkę pikseli

Stwórzmy siatkę pikseli, której możesz użyć do tworzenia pikselowej sztuki.

Siatka będzie wyglądać jak tabela. Tabele zawierają wiersze, a wiersze zawierają komórki, które będą reprezentować piksele.

+ Otwórz [startowy trinket](http://jumpto.cc/web-pixel).

Projekt powinien wyglądać następująco:

![zrzut ekranu](images/pixel-starter.png)

Najpierw napiszmy kod, aby utworzyć tabelę z czarnym tłem, a następnie wstawić do niej białe piksele.

+ Dodaj ten kod do `<body>`twojego pliku `index.html`, aby utworzyć `<div>`:

![zrzut ekranu](images/pixel-art-art.png)

`<div>` to niewidzialne pole któremu możesz nadać **styl**. Ten `<div>` ma identyfikator `art`, którego potrzebujesz, aby móc dodawać style do pola.

+ Teraz przejdź do pliku `style.css` i dodaj styl tabeli dla `<div>` o nazwie `art`.

![zrzut ekranu](images/pixel-art-style.png)

Tworzy to tabelę z ramką i ustawia odstępy wewnątrz siatki.

Nie wygląda to jeszcze zbyt interesująco, więc musisz umieścić w nim rzędy pikseli.

+ Wróć do swojego pliku `index.html` i dodaj wiersz z trzema pikselami **w środku** pola `art`. Jeśli chcesz zaoszczędzić czas, możesz wpisać pierwszy wiersz, a następnie skopiować i wkleić go, aby utworzyć pozostałe.

![zrzut ekranu](images/pixel-art-row.png)

Zauważ, że używasz **klasy** zamiast identyfikatora, aby ustawić styl elementów div. Jest tak, ponieważ będzie ich wiele, więc klasa jest bardziej przydatna.

+ Przejdź do pliku `style.css` i dodaj następujące style dla wierszy i pikseli w każdym wierszu:

![zrzut ekranu](images/pixel-art-row-style.png)

Teraz twoje piksele ustawią się w siatce z czarnymi liniami wokół nich.

+ W swoim pliku `index.html` dodaj kolejne dwie sekcje pikseli, aby utworzyć siatkę o wymiarach 3 × 3 pikseli. Możesz ponownie skopiować i wkleić, aby zaoszczędzić czas.

\--- hints \--- \--- hint \--- Znajdź znacznik `<div>` z klasą `row` i skopiuj go, w tym trzy wiersze oznaczone `pixel` które są w środku, wliczając jego znacznik `</div>`.

Wklej ten kod bezpośrednio pod sekcją, którą właśnie skopiowałeś, aby utworzyć kolejny wiersz. Powtórz jeszcze raz, aby mieć trzy rzędy po trzy piksele.

Możesz sprawdzić, czy twoja tabela wygląda prawidłowo, patrząc na wynik po prawej. \--- /hint \--- \--- hint \--- Tak powinien wyglądać twój kod:

![zrzut ekranu](images/pixel-art-grid-3.png) \--- /hint \--- \--- /hints \---