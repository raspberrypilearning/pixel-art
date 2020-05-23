## Crea una cuadrícula de píxeles

Vamos a crear una cuadrícula de píxeles que puedes usar para crear pixel art.

La cuadrícula se verá como una tabla. Las tablas contienen filas y las filas contienen celdas que representarán los píxeles.

+ Abre el [trinket de iniciación](http://jumpto.cc/web-pixel).

El proyecto deberá parecerse a esto:

![captura de pantalla](images/pixel-starter.png)

First, let's write some code to create a table with a black background and then put white pixels into it.

+ Add this code into the `<body>` of your `index.html` file to create a `<div>`:

![captura de pantalla](images/pixel-art-art.png)

A `<div>` is an invisible box to which you can give a **style**. Este `<div>` tiene el ID `art`, que necesitas para que puedas añadir estilos a la caja.

+ Ahora ve a tu archivo `style.css` y agrega el estilo de tabla para el `<div>` llamado `art`.

![captura de pantalla](images/pixel-art-style.png)

This creates a table with a border and sets the spacing inside the grid.

Aun no se ve muy interesante, así que hay que poner filas de píxeles en su interior.

+ Vuelve a tu archivo `index.html` y agrega una fila de tres píxeles **dentro** de la caja `arte`. If you want to save time, you can type the first row and then copy and paste it to create the others.

![screenshot](images/pixel-art-row.png)

Notice that here you're using a **class** instead of an ID to style the divs. This is because there will be lots of them, so a class is more useful.

+ Switch to the `style.css` file and add the following styles for the rows and the pixels within each row:

![screenshot](images/pixel-art-row-style.png)

Ahora tus píxeles se alinearán en una cuadrícula con líneas negras a su alrededor.

+ En tu archivo` index.html `, agrega otras dos secciones de píxeles para crear una cuadrícula de 3 × 3. Puedes usar copiar y pegar nuevamente para ahorrar tiempo.

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