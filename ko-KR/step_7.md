## 색깔 팔레트 추가

실수로 검은색을 칠해 버렸을 때 다시 흰색으로 바꾸지 못한다는 것을 알고 계셨나요? 이제 색상 팔레트를 만들어 그 문제를 해결해 봅시다!

+ 아래 코드를 `style.css` 파일에 추가해 펜 스타일을 만들어 봅시다.

![screenshot](images/pixel-art-pen.png)

+ 이제 검은색과 회색 펜 색상 팔레트를 제작하였습니다. 아래 코드를 `index.html` 내 `<body>` 태그 안에 넣어 주십시오.

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

You'll also need use the `penColour` variable when you change the colour of a pixel.

+ Change the `setPixelColour` function to use the `penColour` variable instead of `black`:
    
    ![screenshot](images/pixel-art-use-pen.png)

+ In the `index.html` file, add some code to call the `setPenColour` function when a colour in the palette is clicked.

![screenshot](images/pixel-art-palette-onclick.png)

+ Test that you can switch the pen colour between black and white to fill in or delete pixels.