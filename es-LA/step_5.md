## Colorea los píxeles

Este proyecto usa tres lenguajes diferentes:

+ HTML se usa para organizar tu contenido
+ CSS tells the content what to look like with styles
+ JavaScript es un lenguaje de programación que puedes usar para hacer que una página web responda cuando interactúas con ella

Agreguemos un código JavaScript para colorear un píxel automáticamente cuando haces clic en él.

Vamos a crear una **función**. Las funciones son bloques de código con nombre, que realizan una tarea particular. Podemos ** llamar ** a una función por su nombre cuando queremos ejecutar el código que contiene.

+ Dentro del archivo `script.js`, crea una función con el nombre `setPixelColour`. The `setPixelColour` function needs to take a `pixel` as an **input** so that it can change that pixel's colour.

![Create function](images/create-function.png)

+ Add this code inside the function to set the background colour of the pixel:

![screenshot](images/pixel-art-set-pixel-colour.png)

Notice that `backgroundColor` uses the American spelling of 'colour'.

At the moment this code doesn't have any effect.

+ Go to `index.html` and add the following code to the first pixel so that when you click on this pixel, the `setPixelColour` function is called:

![screenshot](images/pixel-art-onclick.png)

The `this` in the brackets is the input for the `setPixelColour` function, which lets it know which pixel to set the colour for — `this` pixel!

+ Test your code by clicking on the first pixel. It should turn black.

![screenshot](images/pixel-art-black.png)

You've only added `onclick` code to the **first** pixel, so clicking on the other pixels won't do anything yet.