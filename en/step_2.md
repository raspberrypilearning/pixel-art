## Create the grid

Create a grid of pixels you can use to create pixel art.

The grid will look like a table. Tables contain rows, and rows contain cells which represent the pixels.

--- task ---

Open the [starter project](https://editor.raspberrypi.org/en/projects/editor-pixel-art-starter).

--- /task ---

Create a table with black borders.

A `<div>` is an invisible box you can style. 

--- task ---

Add a `<div>` with the ID `art`, so you can style it. 

--- code ---
---
filename: index.html
language: html
line_numbers: true
line_number_start: 7
line_highlights: 8-10
---
<body>
  <div id="art">

  </div>  
</body>

--- /code ---

--- /task ---

Add the styling.

--- task ---

Switch to the `style.css` file and add the styling for the art `<div>`.

--- code ---
---
filename: style.css
language: css
line_numbers: true
line_number_start: 1
---
#art {
  display: table;
  border-spacing: 1px;
  background-color: black;
  border: 5px solid black;
}

--- /code ---

--- /task ---

**Test:** Run your code to see a black dot appear.
