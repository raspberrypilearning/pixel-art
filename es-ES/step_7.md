## Añade una paleta de colores

¿Te molesta que no puedas cambiar el color de un píxel a blanco si cometiste un error? Arreglemos eso creando una paleta de colores para que puedas elegir entre los colores de la pluma con un clic.

+ Agrega este código en la parte inferior de tu archivo ` style.css` para crear un estilo de pluma:

![captura de pantalla](images/pixel-art-pen.png)

+ Ahora crea una paleta con colores blanco y negro usando el estilo que acabas de crear. Agrega el siguiente código a tu ` index.html` debajo de la etiqueta `<body>`:

![captura de pantalla](images/pixel-art-palette.png)

` style = ` permite agregar código CSS dentro de tu archivo HTML, que aquí es conveniente.

Necesitamos agregar código para que cuando se haga clic en uno de los colores de la paleta, cambie el color del lápiz.

+ Cambia a ` script.js ` y crea una variable llamada ` penColour ` en la parte superior del archivo. Establece el valor de la variable a ` 'black' `.

[[[generic-javascript-create-variable]]]

\--- hints \---

\--- hint \---

Add the following code at the top of the file:

![captura de pantalla](images/pixel-art-pencolour.png)

\--- /hint \---

\--- /hints \---

+ Debajo de la variable, crea una nueva función llamada ` setPenColour ` con una entrada de ` pen`. Mira la función ` setPixelColour ` que ya has creado para ayudarte.

[[[generic-javascript-create-a-function]]]

+ Dentro de la función ` setPenColour `, agrega código para asignar el de ` pen` proporcionado como entrada a la variable ` penColour `.

![screenshot](images/pixel-art-set-pen.png)

You'll also need to use the `penColour` variable when you change the colour of a pixel.

+ Cambia la función ` setPixelColour ` para usar la variable ` penColour ` en lugar de ` black `:
    
    ![captura de pantalla](images/pixel-art-use-pen.png)

+ En el archivo `index.html`, agrega código para llamar a la función `setPenColour` cuando se haga clic en un color en la paleta.

![screenshot](images/pixel-art-palette-onclick.png)

+ Prueba que puedes cambiar el color del lápiz entre negro y blanco para pintar o borrar píxeles.