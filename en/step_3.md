## Add a row of pixels

Switch to the `index.html` file.

--- task ---

Add a row of three pixels inside the art div.

**Tip**: If you want to save time, you can type the first row and then copy and paste it to create the others.

--- code ---
---
filename: index.html
language: html
line_numbers: true
line_number_start: 7
line_highlights: 9-13
---
<body>
  <div id="art">
    <div class = "row">
      <div class="pixel"></div>
      <div class="pixel"></div>
      <div class="pixel"></div>
    </div>
  </div>  
</body>

--- /code ---

--- /task --- 

--- task ---

### Style the rows and pixels

Switch to the `style.css` file and add the styles.

--- code ---
---
filename: style.css
language: css
line_numbers: true
line_number_start: 8
---
.row {
  display: table-row;
}

.pixel {
  display: table-cell;
  background-color: white;
  width: 40px;
  height: 40px;
  border: 1px solid black;
}

--- /code ---

--- /task ---

**Notice**: You have used a class instead of an ID to style the row and pixel divs. This is because there will be lots of them.

**Test:** Run your code to see the row of pixels.

### Create a 3×3 pixel grid. 

--- task ---

Switch to the `index.html` file

Add another two sections of pixels to create a 3×3 pixel grid. 

You can use copy and paste again to save time.

--- /task ---

--- hints ---

--- hint ---

Find the `<div>` tag with the class `row` and copy it, including the three rows labelled `pixel` which are inside it, up to and including its matching `</div>` tag.

Paste this code immediately below the section you just copied to create another row. Repeat once more so that you have three rows of three pixels each.

You can check whether your table looks right by looking at the result area on the right.

--- /hint ---

--- hint ---

Here is how your code should look:

--- code ---
---
filename: index.html
language: html
line_numbers: true
line_number_start: 7
line_highlights: 14-23
---
<body>
  <div id="art">
    <div class = "row">
      <div class="pixel"></div>
      <div class="pixel"></div>
      <div class="pixel"></div>
    </div>
    <div class = "row">
      <div class="pixel"></div>
      <div class="pixel"></div>
      <div class="pixel"></div>
    </div>
    <div class = "row">
      <div class="pixel"></div>
      <div class="pixel"></div>
      <div class="pixel"></div>
    </div>
  </div>  
</body>

--- /code ---

--- /hint ---

--- /hints ---

**Test:** Run your code to see the 3x3 grid.