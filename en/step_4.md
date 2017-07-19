## Colour the pixels

HTML is used to organise your content and CSS to style it. JavaScript is a programming language that can be used to change a web page as you interact with it. 

You could use HTML and CSS to set the background colour of individual pixels, but that would be a slow way to work! Instead you're going to add some JavaScript code to colour pixels automatically when you click on them. 

+ In JavaScript, code is placed in a `function` that can be called when we want to run that code. 

	You're going to create a function called `setPixelColour`

	The `setPixelColour` function needs to know which pixel to change the colour of, this is an `input`.

	Add the following code to the `script.js` file to set the background colour of a pixel:

	![screenshot](images/pixel-art-set-pixel-colour.png)

	Notice that `backgroundColor` uses the American spelling of colour. 

+ Now we need to call that function when a pixel is clicked on.

	HTML uses `onclick` to call a function when an element is clicked on. You'll need to pass in 'this' as the input so your function knows which pixel to change the colour of. 

	Go to `index.html` and add the following code to the first pixel:

	![screenshot](images/pixel-art-onclick.png)

+ Test your code by clicking in the first pixel. It should turn black:

	![screenshot](images/pixel-art-black.png)

	You only added `onclick` code to the first pixel so this won't work for the other pixels yet. 


