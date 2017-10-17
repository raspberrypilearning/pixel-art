## Colour the pixels

This project uses three different languages:
- HTML is used to organise your content
- CSS tells the content what to look like with styles
- JavaScript is a programming language that can be used to change a web page when you interact with it

Let's add some JavaScript code to colour in a pixel automatically when you click on it.

We will create a `function`. Functions are named blocks of code which perform a particular task. We can call a function by its name when we want to run the code it contains.

+ Inside **script.js**, create a function with the name `setPixelColour`. The `setPixelColour` function needs to know which `pixel` to change the colour of, this is an `input`.

![Create function](images/create-function.png)

+ Add the code inside the function to set the background colour of the pixel:

![screenshot](images/pixel-art-set-pixel-colour.png)

Notice that `backgroundColor` uses the American spelling of colour.

At the moment this code doesn't have any effect.

+ Go to `index.html` and add the following code to the first pixel so that when the pixel is clicked on, the code calls the function:

![screenshot](images/pixel-art-onclick.png)

The 'this' in the brackets is the input so your function knows which pixel to change the colour of - 'this' pixel!

+ Test your code by clicking in the first pixel. It should turn black:

![screenshot](images/pixel-art-black.png)

You only added `onclick` code to the first pixel so this won't work for the other pixels yet.
