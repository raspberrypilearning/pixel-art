## 픽셀에 색상 입히기

이 프로젝트는 세 가지 다른 언어를 사용합니다.

+ 내용을 구성하기 위해 HTML 사용
+ 스타일을 어떻게 보여줄지 구성하는 CSS 사용
+ 웹페이지 상호 작용을 구현하기 위한 JavaScript 사용

이제 JavaScript 코드를 추가하여 클릭할 때 자동으로 색상을 지정하는 코드를 추가해 보겠습니다.

우리는 **함수**를 제작할 것입니다. 함수는 특정 작업을 수행하는 코드 블록입니다. 해당 블록을 실행하고자 할 때 우리는 함수를 **호출**할 수 있습니다.

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