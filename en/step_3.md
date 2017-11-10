## Create a grid of pixels

Let's create a grid of pixels that you can use for creating pixel art.

The grid will look like a **table**. Tables contain rows, and rows contain cells which will represent the pixels.

+ Open the starter trinket: [jumpto.cc/web-pixel](http://jumpto.cc/web-pixel).

The project should look like this:

![screenshot](images/pixel-starter.png)

First, let's write some code to create a table with a black background and then put white pixels into it.

+ Add this code into the `<body>` of your `index.html` file to create a `<div>`.

![screenshot](images/pixel-art-art.png)

A `<div>` is an invisible box, which you can give a **style** to. This `<div>` has the ID `art` so you can add styles to it.

+ Now go to your `style.css` file and add the table styling for the art `<div>`.

![screenshot](images/pixel-art-style.png)

This creates a table with a border and sets the spacing inside the grid.

It doesn't look very interesting yet, you need to put rows of pixels inside it.

+ Go back to your `index.html` file and add a row of 3 pixels **inside** the art `<div>`:

![screenshot](images/pixel-art-row.png)

Notice that the three pixel lines are the same. Type the first one and then use copy and paste to create the others.

This time you're using a class instead of an ID to style the divs as there will be lots of them.

+ Add the following styles for the rows and the pixels within each row:

![screenshot](images/pixel-art-row-style.png)

Now your pixels will line up in a grid with black lines around them.

+ In your index.html file, add another two rows of pixels to create a 3 x 3 grid. Remember to use copy and paste to save time.

--- hints ---
--- hint ---
Find the `<div>` with the class "row" and copy it, including the three pixels which are inside it, up to and including its matching `</div>` tag.

Paste this in immediately below the row you just copied to create another row. Repeat once more so that you have three rows.

You can check whether your table looks right by looking at the result area on the right of your code.
--- /hint ---
--- hint ---
Here is how your code should look:

![screenshot](images/pixel-art-grid-3.png)
--- /hint ---
--- /hints ---
