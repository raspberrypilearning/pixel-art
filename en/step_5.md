## Colour the pixels

This project uses three different languages:
- HTML is used to organise your content
- CSS tells the content what to look like with styles
- JavaScript is a programming language you can use to make a webpage respond when you interact with it

Let's add some JavaScript code to colour in a pixel automatically when you click on it.

We will create a **function**. Functions are named blocks of code which perform a particular task. We can **call** a function by its name when we want to run the code it contains.

+ Inside the `script.js` file, create a function with the name `setPixelColour`. The `setPixelColour` function needs to take a `pixel` as an **input** so that it can change that pixel's colour.

![Create function](images/create-function.png)

+ Add this code inside the function to set the background colour of the pixel:

![screenshot](images/pixel-art-set-pixel-colour.png)

Notice that `backgroundColor` uses the American spelling of 'colour'.

At the moment this code doesn't have any effect.

+ Go to `index.html` and add the following code to the first pixel so that when you click on this pixel, the `setPixelColour` function is called:

![screenshot](images/pixel-art-onclick.png)

The `this` in the brackets is the input for the `setPixelColour` function, which lets it know which pixel to set the colour for — `this` pixel!

+ Test your code by clicking on the first pixel. It should turn black.

![screenshot](images/pixel-art-black.png)

You've only added `onclick` code to the **first** pixel, so clicking on the other pixels won't do anything yet.
