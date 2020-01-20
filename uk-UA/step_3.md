## Створіть сітку пікселів

Створімо сітку пікселів, які можна використовувати для створення піксельного мистецтва.

Сітка виглядатиме як таблиця. Таблиці містять рядки, а рядки містять комірки, які представлятимуть пікселі.

+ Відкрийте [starter trinket](http://jumpto.cc/web-pixel).

Проект повинен виглядати так:

![знімок екрану](images/pixel-starter.png)

Спочатку давайте напишемо код, щоб створити таблицю з чорним фоном, а потім додати в неї білі пікселі.

+ Додайте цей код у `<body>` свого ` index.html` файлу, щоб створити `<div>` :

![знімок екрану](images/pixel-art-art.png)

A `<div>` - це невидиме поле, на яке ви можете натиснути **стиль**. Цей `<div>` має ідентифікатор ` art ` , який вам потрібний, щоб ви могли додати стилі до коробки.

+ Тепер перейдіть до вашого ` style.css` файлу та додайте стиль таблиці для `<div>` називається `art` .

![знімок екрану](images/pixel-art-style.png)

Це створює таблицю з межами і встановлює інтервал всередині сітки.

Це ще не виглядає дуже цікаво, тому вам потрібно помістити в нього рядки пікселів.

+ Поверніться до свого ` index.html ` файлу і додайте рядок з трьох пікселів ** усередині ** ` art ` коробки Якщо ви хочете заощадити час, ви можете ввести перший рядок, а потім скопіювати та вставити його, щоб створити інші.

![знімок екрану](images/pixel-art-row.png)

Зверніть увагу, що тут ви використовуєте **class** замість ID, до стилю відділення. Оскільки буде велика кількість їх, тому клас більш корисний.

+ Перейдіть до ` style.css ` файл і додайте наступні стилі для рядків та пікселів у кожному рядку:

![знімок екрану](images/pixel-art-row-style.png)

Тепер ваші пікселі вирівняються в сітці з чорними лініями навколо них.

+ У своєму ` index.html ` файл, додайте ще дві секції пікселів, щоб створити 3 × 3 піксельну сітку. Ви можете скопіювати та вставити ще раз, щоб заощадити час.

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