## Add a colour palette

Did you find it annoying that you couldn't change a pixel's colour back to white if you made a mistake? Let's fix that by creating a colour palette so that you can choose between pen colours with a click.

+ Add this code at the bottom of your `style.css` file to create a pen style:

![screenshot](images/pixel-art-pen.png)

+ Now create a palette with black and white pen colours using the pen style you just created. Add the following code to your `index.html` below the `<body>` tag:

![screenshot](images/pixel-art-palette.png)

`style=` allows you to add CSS code inside your HTML file, which is convenient here.

We need to add code so that when one of the colours in the palette is clicked on, the colour of the pen changes.

+ Switch to `script.js` and create a variable called `penColour` at the very top of the file. Set the value of the variable to `'black'`.

[[[generic-javascript-create-variable]]]

--- hints ---
--- hint ---
Add the following code at the top of the file:

![screenshot](images/pixel-art-pencolour.png)
--- /hint ---
--- /hints ---

+ Below the variable, create a new function called `setPenColour` with an input of `pen`. Look at the function `setPixelColour` that you already created to help you.

[[[generic-javascript-create-a-function]]]

+ Inside the `setPenColour` function, add code to set the `penColour` variable to the `pen` colour provided as the input.

![screenshot](images/pixel-art-set-pen.png)

You'll also need to use the `penColour` variable when you change the colour of a pixel.

+ Change the `setPixelColour` function to use the `penColour` variable instead of `black`:

 ![screenshot](images/pixel-art-use-pen.png)

+ In the `index.html` file, add some code to call the `setPenColour` function when a colour in the palette is clicked.

![screenshot](images/pixel-art-palette-onclick.png)

+ Test that you can switch the pen colour between black and white to fill in or delete pixels.
