## Crear una cuadrícula de píxeles

Vamos a crear una cuadrícula de píxeles que se pueden utilizar para la creación de arte de pixel.

La cuadrícula se verá como una tabla. Las tablas contienen filas, y las filas contienen celdas que representarán los píxeles.

+ Abre el [trinket de inicio](http://jumpto.cc/web-pixel).

El proyecto debería parecerse a esto:

![captura de pantalla](images/pixel-starter.png)

En primer lugar, vamos a escribir algo de código para crear una tabla con un fondo negro y luego poner píxeles blancos en él.

+ Agrega este código dentro del `<body>` del archivo `index.html` para crear un `<div>`:

![captura de pantalla](images/pixel-art-art.png)

Un `<div>` es una caja invisible a la que le puedes dar un **estilo**. Este `<div>` tiene el ID `arte`, que necesitas para que puedas añadir estilos a la caja.

+ Ahora ve a tu archivo `style.css` y agrega el estilo de tabla para el `<div>` llamado `art`.

![captura de pantalla](images/pixel-art-style.png)

Esto crea una tabla con un borde y establece el espaciado interno de la cuadrícula.

Todavía no se ve muy interesante, por lo que necesitarás poner filas de píxeles dentro de ella.

+ Vuelve a tu archivo `index.html` y añade una fila de tres píxeles **dentro** de la caja `art`. Si deseas ahorrar tiempo, puedes escribir la primera fila y luego copiar y pegar para crear las otras.

![captura de pantalla](images/pixel-art-row.png)

Ten en cuenta que aquí estás usando una **class ** en lugar de una ID para diseñar los divs. Esto se debe a que habrá muchos de ellos, por lo que una clase es más útil.

+ Cambia al archivo ` style.css ` y agrega los siguientes estilos para las filas y los píxeles dentro de cada fila:

![captura de pantalla](images/pixel-art-row-style.png)

Ahora tus píxeles se alinearán en una cuadrícula con líneas negras a su alrededor.

+ En tu archivo` index.html `, agrega otras dos secciones de píxeles para crear una cuadrícula de 3 × 3 píxeles. Puedes usar copiar y pegar nuevamente para ahorrar tiempo.

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