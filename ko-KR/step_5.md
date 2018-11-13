## 픽셀에 색상 입히기

이 프로젝트는 세 가지 다른 언어를 사용합니다.

+ 내용을 구성하기 위해 HTML 사용
+ 스타일을 어떻게 보여줄지 구성하는 CSS 사용
+ 웹페이지 상호 작용을 구현하기 위한 JavaScript 사용

이제 JavaScript 코드를 추가하여 클릭할 때 자동으로 색상을 지정하는 코드를 추가해 보겠습니다.

우리는 **함수**를 제작할 것입니다. 함수는 특정 작업을 수행하는 코드 블록입니다. 해당 블록을 실행하고자 할 때 우리는 함수를 **호출**할 수 있습니다.

+ `script.js` 파일에 들어가서, `setPixelColour` 함수를 제작하십시오. `setPixelColour` 함수는 `pixel`을 **입력**으로 받아 픽셀의 색깔을 바꿀 수 있도록 설정해 주는 함수입니다.

![Create function](images/create-function.png)

+ 아래 코드를 함수 안에 추가하여 픽셀의 배경색을 설정하세요.

![screenshot](images/pixel-art-set-pixel-colour.png)

`backgroundColor`는 'colour'라는 미국식 철자를 사용합니다.

아직 이 코드는 아무런 효과가 없습니다.

+ Go to `index.html` and add the following code to the first pixel so that when you click on this pixel, the `setPixelColour` function is called:

![screenshot](images/pixel-art-onclick.png)

The `this` in the brackets is the input for the `setPixelColour` function, which lets it know which pixel to set the colour for — `this` pixel!

+ Test your code by clicking on the first pixel. It should turn black.

![screenshot](images/pixel-art-black.png)

You've only added `onclick` code to the **first** pixel, so clicking on the other pixels won't do anything yet.