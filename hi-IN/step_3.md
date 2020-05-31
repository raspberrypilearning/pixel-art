## पिक्सेल का ग्रिड बनाएँ

Let's create a grid of pixels that you can use for creating pixel art.

ग्रिड यह एक तालिका की तरह दिखेगा। तालिकाओं में पंक्तियाँ होती हैं, और पंक्तियों में जो कोशिकाएँ होती हैं वो पिक्सेल का प्रतिनिधित्व करती हैं।

+ [स्टार्टर ट्रिंकेट](http://jumpto.cc/web-pixel) खोलें।

प्रोजैक्ट इस तरह दिखनी चाहिए:

![स्क्रीनशॉट](images/pixel-starter.png)

सबसे पहले, एक काले रंग की पृष्ठभूमि के साथ एक तालिका बनाने के लिए कोड लिखें और फिर इसमें कुछ सफेद पिक्सेल डालें।

+ Add this code into the `<body>` of your `index.html` file to create a `<div>`:

![screenshot](images/pixel-art-art.png)

A `<div>` is an invisible box to which you can give a **style**. This `<div>` has the ID `art`, which you need so you can add styles to the box.

+ Now go to your `style.css` file and add the table styling for the `<div>` called `art`.

![screenshot](images/pixel-art-style.png)

This creates a table with a border and sets the spacing inside the grid.

It doesn't look very interesting yet, so you need to put rows of pixels inside it.

+ Go back to your `index.html` file and add a row of three pixels **inside** the `art` box. If you want to save time, you can type the first row and then copy and paste it to create the others.

![screenshot](images/pixel-art-row.png)

Notice that here you're using a **class** instead of an ID to style the divs. This is because there will be lots of them, so a class is more useful.

+ Switch to the `style.css` file and add the following styles for the rows and the pixels within each row:

![screenshot](images/pixel-art-row-style.png)

Now your pixels will line up in a grid with black lines around them.

+ In your `index.html` file, add another two sections of pixels to create a 3×3 pixel grid. You can use copy and paste again to save time.

\--- hints \---

\--- hint \---

Find the `<div>` tag with the class `row` and copy it, including the three rows labelled `pixel` which are inside it, up to and including its matching `</div>` tag.

Paste this code immediately below the section you just copied to create another row. Repeat once more so that you have three rows of three pixels each.

You can check whether your table looks right by looking at the result area on the right.

\--- /hint \---

\--- hint \---

Here is how your code should look:

![screenshot](images/pixel-art-grid-3.png)

\--- /hint \---

\--- /hints \---