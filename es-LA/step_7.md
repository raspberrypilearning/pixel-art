## Agrega una paleta de colores

¿Te molesta que no puedas cambiar el color de un píxel a blanco si cometiste un error? Arreglemos eso creando una paleta de colores para que puedas elegir entre los colores del lápiz con un clic.

+ Agrega este código en la parte inferior de tu archivo `style.css` para crear un estilo de lápiz:

![captura de pantalla](images/pixel-art-pen.png)

+ Ahora crea una paleta con colores blanco y negro usando el estilo que acabas de crear. Agrega el siguiente código a tu `index.html` debajo de la etiqueta `<body>`:

![captura de pantalla](images/pixel-art-palette.png)

`style=` permite agregar el código CSS dentro de tu archivo HTML, que aquí es conveniente.

Necesitamos agregar el código para que cuando se haga clic en uno de los colores de la paleta, cambie el color del lápiz.

+ Cambia a `script.js` y crea una variable llamada `penColour` en la parte superior del archivo. Establece el valor de la variable a `'black'`.

[[[generic-javascript-create-variable]]]

--- hints ---


--- hint ---

Agrega el siguiente código en la parte superior del archivo:

![captura de pantalla](images/pixel-art-pencolour.png)

--- /hint ---

--- /hints ---

+ Debajo de la variable, crea una nueva función llamada `setPenColour` con una entrada de `pen`. Observa la función `setPixelColour` que ya has creado para ayudarte.

[[[generic-javascript-create-a-function]]]

+ Dentro de la función `setPenColour`, agrega el código para asignar el de `pen` proporcionado como entrada a la variable `penColour`.

![captura de pantalla](images/pixel-art-set-pen.png)

También necesitarás usar la variable `penColour` cuando cambies el color de un píxel.

+ Cambia la función `setPixelColour` para usar la variable `penColour` en lugar de `black`:
    
    ![captura de pantalla](images/pixel-art-use-pen.png)

+ En el archivo `index.html`, agrega el código para llamar a la función `setPenColour` cuando se haga clic en un color en la paleta.

![captura de pantalla](images/pixel-art-palette-onclick.png)

+ Prueba que puedes cambiar el color del lápiz entre negro y blanco para pintar o borrar píxeles.