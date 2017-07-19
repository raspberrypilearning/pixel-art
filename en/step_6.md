## Add a colour palette

Did you find it annoying that you couldn't change a pixel colour back to white if you made a mistake? Let's fix that by creating a colour palette so that you can click on a colour to change the pen. 

+ First create a pen style. 

	Add the following code at the bottom of your `style.css` file:

	![screenshot](images/pixel-art-pen.png)

+ Now create black and white pen colours that use that style. 

	Add the following code to your `index.html` after the `<body>`:

	![screenshot](images/pixel-art-palette.png)

	`style=` allows you to add CSS inside your HTML which is convient here. 

+ You want to be able to change the pen colour when a palette colour is clicked on. 

	Variables are used to store information. Let's create a penColour variable in `script.js`.

	Add the following code at the top of the file:

	![screenshot](images/pixel-art-pencolour.png)

	Then add a function to change the penColour:

	![screenshot](images/pixel-art-set-pen.png)

+ You'll also need use the pen colour when you change the colour of a pixel. 

	Change the `setPixelColour` function to use the `penColour` variable instead of `black`:

	 ![screenshot](images/pixel-art-use-pen.png)

+ Now you need to call the `setPenColour` function when a pen colour gets clicked. 

	Add the highlighted `onclick` code to your pen colours:

	![screenshot](images/pixel-art-palette-onclick.png)

+ Now test that you can switch the pen colour between black and white to fill in or delete pixels.




