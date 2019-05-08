## Desafío: Modifica el tamaño de la cuadrícula

Vamos a crear una cuadrícula de píxeles que se pueden utilizar para la creación de arte de pixel.

La grilla se verá como una tabla. Las tablas contienen filas y las filas contienen celdas que representarán los píxeles.

+ Abre el [starter trinket](http://jumpto.cc/web-pixel).

El proyecto debería parecerse a esto:

![captura de pantalla](images/pixel-starter.png)

En primer lugar, vamos a escribir algo de código para crear una tabla con un fondo negro y luego poner píxeles blancos en él.

+ Agrega este código en el `<body>` archivo ` index.html` para crear un `<div>`:

![captura de pantalla](images/pixel-art-art.png)

Un `<div>`es una caja invisible a la que le puedes dar un **style**. Este `<div>`tiene el ID `arte`, que necesita para poder añadir estilos a la caja.

+ Ahora ve a tu archivo `style.css` y agrega el estilo de tabla para el `<div>`llamado `art`.

![captura de pantalla](images/pixel-art-style.png)

Esto crea una tabla con un borde y establece el espaciado interno de la cuadrícula.

Todavía no se ve muy interesante, por lo que necesita poner filas de píxeles dentro de él.

+ Regresa a tu archivo ` index.html ` y agrega una fila de tres píxeles ** adentro** de la caja de ` art`. Si deseas ahorrar tiempo, puede escribir la primera fila y luego copiar y pegar para crear las otras.

![captura de pantalla](images/pixel-art-row.png)

Ten en cuenta que aquí estás usando una **class ** en lugar de una ID para diseñar los divs. Esto se debe a que habrá muchos de ellos, por lo que una clase es más útil.

+ Cambia al archivo ` style.css ` y agrega los siguientes estilos para las filas y los píxeles dentro de cada fila:

![captura de pantalla](images/pixel-art-row-style.png)

Ahora tus píxeles se alinearán en una cuadrícula con líneas negras alrededor de ellos.

+ En tu archivo` index.html `, agrega otras dos secciones de píxeles para crear una cuadrícula de 3 × 3 píxeles. Puede usar copiar y pegar nuevamente para ahorrar tiempo.

\--- hints \--- \--- hint \--- Encuentra la `<div>` etiqueta de la clase ` row` y cópielo, incluidas las tres filas llamadas ` pixel` que están dentro de él, hasta e incluyendo su etiqueta` </div>` que coincide.

Pegue este código inmediatamente debajo de la sección que acaba de copiar para crear otra fila. Repita una vez más para tener tres filas de tres píxeles cada una.

Puede verificar si su mesa se ve bien al mirar el área de resultados a la derecha. \--- / hint \--- \--- hint \--- Así es como debe verse tu código:

![captura de pantalla](images/pixel-art-grid-3.png) \--- /hint \--- \--- /hints \---