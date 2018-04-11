## Colorea los píxeles

HTML se usa para organizar los contenidos, y CSS para darle estilo. JavaScript es un lenguaje de programación que se puede usar para cambiar una página web al interactuar con ella. 

Podrías usar HTML y CSS para cambiar el color de fondo de cada uno de los píxeles, ¡pero sería muy lento! En lugar de eso, vamos a añadir código de JavaScript para colorear los píxeles de forma automática cuando hagas clic en ellos. 

+ En JavaScript, el código se escribe en una `función` a la que podemos llamar cuando queramos ejecutar ese código. 

	Vamos a crear una función que se llame `establecerColorPixel`

	La función `establecerColorPixel` necesita saber a qué píxel tiene que cambiar el color; esto es una entrada o `input`.

	Añade el siguiente código en el archivo `script.js` para establecer el color de fondo de un píxel:

	![screenshot](images/pixel-art-set-pixel-colour.png)

	¿Te has fijado en que `backgroundColor` se escribe siguiendo las normas de la ortografía estadounidense, y no la británica (colour)?. 

+ Ahora tenemos que llamar a esta función cada vez que se haga clic en un píxel.

	En HTML se usa `onclick` para llamar una función cuando se hace clic en un elemento. Tendrás que pasar la expresión 'this' como el input para que la función identifique a qué píxel debe cambiar el color. 

	Ve a `index.html` y añade el siguiente código al primer píxel:

	![screenshot](images/pixel-art-onclick.png)

+ Prueba el código haciendo clic en el primer píxel. Debería volverse negro:

	![screenshot](images/pixel-art-black.png)

	Solo has añadido el código `onclick` en el primer píxel, así que en el resto de píxeles no funcionará aún. 
