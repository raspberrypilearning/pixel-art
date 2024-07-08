## Create a colour palette

Add a new table

--- task ---

Switch to the `style.css` file and create a pen style.

--- code ---
---
filename: style.css
language: css
line_numbers: true
line_number_start: 12
line_highlights: 20-25
---
.pixel {
  display: table-cell;
  background-color: white;
  width: 40px;
  height: 40px;
  border: 1px solid black;
}

.pen {
  display: inline-block;
  width: 40px;
  height: 40px;
  border: 2px solid black;
}

--- /code ---

--- /task ---

--- task ---

Switch to the `index.html` file and add a black and white palette.

--- code ---
---
filename: index.html
language: html
line_numbers: true
line_number_start: 7
line_highlights: 8-11
---
<body>
  <div id="palette">
    <div class="pen" style="background-color:white;"></div>
    <div class="pen" style="background-color:black;"></div>
  </div>
  <div id="art">
  <div class = "row">

--- /code ---

--- /task ---

**Test:** Run your code. You should see your palette at the top.

**Debug**: Notice that the styles for the `pen` class end with a semicolon (`;`).

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

You'll also need use the `penColour` variable when you change the colour of a pixel.

+ Change the `setPixelColour` function to use the `penColour` variable instead of `black`:

 ![screenshot](images/pixel-art-use-pen.png)

+ In the `index.html` file, add some code to call the `setPenColour` function when a colour in the palette is clicked.

![screenshot](images/pixel-art-palette-onclick.png)

+ Test that you can switch the pen colour between black and white to fill in or delete pixels.
