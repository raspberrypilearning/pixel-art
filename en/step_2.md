## Creating a grid of pixels

Let's create a grid of pixels that you can use for creating pixel art. CSS provides table styles for grid and table layouts. 

Tables contain rows which contain cells. You are going to create a table with a black background and then put white pixels into it. 



+ Open this trinket: <a href="http://jumpto.cc/web-pixel" target="_blank">jumpto.cc/web-pixel</a>. 

	The project should look like this:

	![screenshot](images/pixel-starter.png)

+ Add the following html into the `<body>` of your `index.html` file to create a `<div>` as a container for your pixel art and give it an `art` id so you can style it:

	![screenshot](images/pixel-art-art.png)

+ Now go to your `style.css` file and add the table styling for the art `<div>`.

	![screenshot](images/pixel-art-style.png)

	This creates a table with a border and sets the spacing inside the grid. 

	It doesn't look very interesting yet, you need to put rows of pixels inside it. 

 + Now go back to your `index.html` file and add a row of 3 pixels inside the art `<div>`:

	![screenshot](images/pixel-art-row.png)
	
	 Notice that the three pixel lines are the same. Type the first one and then use copy and paste to create the others. 

 	This time you're using classes to style the divs as there will be lots of them. 

 + Add the following style for the rows and cells:

	![screenshot](images/pixel-art-row-style.png)

 	Now your pixels will line up in a grid with black lines around them. 

 + Now add another two rows of pixels to create a 3 x 3 grid. Remember to use copy and paste to save time. 

	![screenshot](images/pixel-art-grid-3.png)
	
    
