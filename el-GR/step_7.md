## Πρόσθεσε χρωματική παλέττα

Δεν βρήκες ενοχλητικό ότι δεν μπορούσες να ξανακάνεις λευκό ένα εικονοστοιχείο, σε περίπτωση λάθους; Διόρθωσέ το αυτό δημιουργώντας μια χρωματική παλέττα, ώστε να μπορείς να επιλέξεις κάποιο χρώμα με ένα κλικ.

+ Πρόσθεσε αυτόν τον κώδικα στο τέλος του αρχείου `style.css` για να δημιουργήσεις ένα στυλ για το μολύβι:

![screenshot](images/pixel-art-pen.png)

+ Τώρα κάνε μια παλέττα με άσπρα και μαύρα χρώματα μολυβιού χρησιμοποιώντας το στυλ μολυβιού που μόλις δημιούργησες. Πρόσθεσε τον παρακάτω κώδικα στο αρχείο `index.html` κάτω από την ετικέτα `<body>`:

![screenshot](images/pixel-art-palette.png)

`style=` allows you to add CSS code inside your HTML file, which is convenient here.

We need to add code so that when one of the colours in the palette is clicked on, the colour of the pen changes.

+ Switch to `script.js` and create a variable called `penColour` at the very top of the file. Set the value of the variable to `'black'`.

[[[generic-javascript-create-variable]]]

\--- hints \--- \--- hint \--- Add the following code at the top of the file:

![screenshot](images/pixel-art-pencolour.png) \--- /hint \--- \--- /hints \---

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