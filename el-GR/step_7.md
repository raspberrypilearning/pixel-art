## Πρόσθεσε χρωματική παλέτα

Δεν βρήκες ενοχλητικό ότι δεν μπορούσες να ξανακάνεις λευκό ένα εικονοστοιχείο, σε περίπτωση λάθους; Διόρθωσέ το αυτό δημιουργώντας μια χρωματική παλέτα, ώστε να μπορείς να επιλέξεις κάποιο χρώμα με ένα κλικ.

+ Πρόσθεσε αυτόν τον κώδικα στο τέλος του αρχείου `style.css` για να δημιουργήσεις ένα στυλ για το μολύβι:

![screenshot](images/pixel-art-pen.png)

+ Τώρα κάνε μια παλέτα με άσπρα και μαύρα χρώματα μολυβιού χρησιμοποιώντας το στυλ μολυβιού που μόλις δημιούργησες. Πρόσθεσε τον παρακάτω κώδικα στο αρχείο `index.html` κάτω από την ετικέτα `<body>`:

![screenshot](images/pixel-art-palette.png)

`style=` σου επιτρέπει να προσθέσεις CSS κώδικα μέσα στο αρχείο HTML, το οποίο είναι βολικό εδώ.

Πρέπει να προσθέσεις κώδικα έτσι ώστε όταν πατηθεί ένα από τα χρώματα της παλέτας, το χρώμα του μολυβιού να αλλάζει.

+ Πήγαινε στο αρχείο `script.js` και δημιούργησε μια μεταβλητή με όνομα `penColour` στην αρχή του αρχείου. Όρισε την τιμή της μεταβλητής σε `'black'`.

[[[generic-javascript-create-variable]]]

\--- hints \--- \--- hint \--- Πρόσθεσε τον ακόλουθο κώδικα στην αρχή του αρχείου:

![screenshot](images/pixel-art-pencolour.png) \--- /hint \--- \--- /hints \---

+ Κάτω από τη μεταβλητή, δημιούργησε μια νέα συνάρτηση με όνομα `setPenColour` με όρισμα τη λέξη `pen`. Δες τη συνάρτηση `setPixelColour` που ήδη έχεις δημιουργήσει για να σε βοηθήσει.

[[[generic-javascript-create-a-function]]]

+ Μέσα στη συνάρτηση `setPenColour` πρόσθεσε κώδικα ώστε να ορίσεις τη μεταβλητή `penColour` με το χρώμα που θα περαστεί μέσω του ορίσματος `pen`.

![screenshot](images/pixel-art-set-pen.png)

You'll also need to use the `penColour` variable when you change the colour of a pixel.

+ Change the `setPixelColour` function to use the `penColour` variable instead of `black`:
    
    ![screenshot](images/pixel-art-use-pen.png)

+ In the `index.html` file, add some code to call the `setPenColour` function when a colour in the palette is clicked.

![screenshot](images/pixel-art-palette-onclick.png)

+ Test that you can switch the pen colour between black and white to fill in or delete pixels.