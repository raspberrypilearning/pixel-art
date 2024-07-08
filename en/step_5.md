## Colour the pixels

Colour a pixel when you click it.

--- task --- 

Switch to the `script.js` file and change the backgroundColor from `'black'` to a colour of your choice. 

--- code ---
---
filename: script.js
language: javascript
line_numbers: true
line_number_start: 1
line_highlights: 2

---
function setPixelColour(pixel) {
  pixel.style.backgroundColor = "black";
}

--- /code ---

--- /task ---

**Tip**: A pixel is passed to the function, so the function can change that pixel’s colour.

At the moment this code doesn't have any effect.

Switch to the `index.html` file and add an `onclick` event to the first `pixel` div.

--- code ---
---
filename: index.html
language: html
line_numbers: true
line_number_start: 7
line_highlights: 10
---
<body>
  <div id="art">
    <div class = "row">
      <div class="pixel" onclick="setPixelColour(this)"></div>
      <div class="pixel"></div>
      <div class="pixel"></div>

--- /code ---

**Tip**: The `this` in brackets is passed to the `setPixelColour` function, so it knows which pixel to colour — ***this*** pixel!

**Test:** Run your code and click on the first pixel. It should turn black.

**Debug**: `backgroundColor` uses the American spelling of 'colour'.

You've only added `onclick` code to the **first** pixel, so clicking on the other pixels won't do anything yet.
