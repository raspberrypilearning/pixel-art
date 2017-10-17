## Add a colour palette

Did you find it annoying that you couldn't change a pixel colour back to white if you made a mistake? Let's fix that by creating a colour palette so that you can click on a colour to change the pen.

+ Add the following code at the bottom of your `style.css` file to create a pen style:

![screenshot](images/pixel-art-pen.png)

+ Now create a palette with black and white pen colours using the pen style you just created. Add the following code to your `index.html` after the `<body>`:

![screenshot](images/pixel-art-palette.png)

`style=` allows you to add CSS inside your HTML which is convenient here.

When one of the colours in the palette is clicked on, the colour of the pen should change.

+ Switch to `script.js` and create a variable called `penColour` at the very top of the file. Set the value to `'black'`.

[[[generic-javascript-create-variable]]]

--- hints ---
--- hint ---
Add the following code at the top of the file:

![screenshot](images/pixel-art-pencolour.png)
--- /hint ---
--- /hints ---

+ Underneath the variable, create a function called `setPenColour`.

+ Inside the `setPenColour` function, add code to set the `penColour` variable to the `pen` colour provided as the input.

![screenshot](images/pixel-art-set-pen.png)

You'll also need use the pen colour when you change the colour of a pixel.

+ Change the `setPixelColour` function to use the `penColour` variable instead of `black`:

 ![screenshot](images/pixel-art-use-pen.png)

+ In the **index.html** file, call the `setPenColour` function when a pen colour gets clicked.

--- hints ---
--- hint ---
Find the `<div>`s with the ID `pen` that you created earlier. Add some `onclick` code to each div to call the function `setPenColour` when the box is clicked. For example, here is the code you would add to the white pen `<div>`.

```JavaScript
onclick="setPenColour('white')"
```
--- /hint ---
--- hint ---
Add the highlighted `onclick` code to your pen colours:

![screenshot](images/pixel-art-palette-onclick.png)
--- /hint ---
--- /hints ---

+ Test that you can switch the pen colour between black and white to fill in or delete pixels.
