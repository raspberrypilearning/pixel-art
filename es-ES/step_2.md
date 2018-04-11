## Crear una cuadrícula de píxeles

Vamos a crear una cuadrícula de píxeles que puedas usar para crear pixel art. CSS tiene estilos de tabla para diseñar cuadrículas y tablas. 

Las tablas contienen filas que contienen celdas. Vamos a crear una tabla de fondo negro, y le vamos a añadir píxeles de color blanco. 

+ Abre este trinket: <a href="http://jumpto.cc/web-pixel" target="_blank">jumpto.cc/web-pixel</a>. Si estás leyendo este proyecto en línea, también puedes usar el trinket incrustado que encontrarás a continuación. 

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/705f264f59" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

+ Añade el siguiente html en el `<body>` (cuerpo) del archivo `index.html` para crear un `<div>` que contenga tu pixel art, y asígnale un id `art` para que le puedas dar estilo:

![screenshot](images/pixel-art-art.png)

 	A continuación, selecciona el archivo `style.css` y añade el estilo de tabla en el `<div>` art. Fíjate en que las tres líneas de píxel son iguales. Escribe la primera, y usa copiar y pegar para crear las demás. 

![screenshot](images/pixel-art-style.png)

	Esto crea una tabla con borde, y establece la separación dentro de la cuadrícula. 

	Todavía no parece muy interesante, ya que tienes que añadir filas de píxeles dentro de la cuadrícula. 

 + Vuelve al archivo `index.html` y añade una fila de 3 píxeles dentro del `<div>` art:

![screenshot](images/pixel-art-row.png)

 	En esta ocasión, estás usando categorías ("class") para dar estilo a los divs, ya que habrá varios de ellos. 

 	Añade el siguiente estilo a las filas y celdas:

![screenshot](images/pixel-art-row-style.png)

 	Ahora tus píxeles se alinearán en una cuadrícula con líneas negras alrededor. 

 + A continuación, añade otras dos filas de píxeles para crear una cuadrícula de 3 x 3. Recuerda usar copiar y pegar para ir más rápido. 

![screenshot](images/pixel-art-grid-3.png)
