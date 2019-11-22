## 색깔 팔레트 추가

실수로 검은색을 칠해 버렸을 때 다시 흰색으로 바꾸지 못한다는 것을 알고 계셨나요? 이제 색상 팔레트를 만들어 그 문제를 해결해 봅시다!

+ 아래 코드를 `style.css` 파일에 추가해 펜 스타일을 만들어 봅시다.

![screenshot](images/pixel-art-pen.png)

+ 이제 검은색과 회색 펜 색상 팔레트를 제작하였습니다. 아래 코드를 `index.html` 내 `<body>` 태그 안에 넣어 주십시오.

![스크린샷](images/pixel-art-palette.png)

`style=`은 CSS 코드를 HTML 파일에 넣을 수 있도록 해 줍니다. 편리하게 사용할 수 있는 기능이니 참고하시기 바랍니다.

팔레트의 색깔 중 하나를 클릭하면 펜의 색상이 변경되도록 코드를 추가할 것입니다.

+ `script.js` 파일에서 `penColour` 변수를 코드의 제일 위에 만드세요. 그리고 변수의 값을 `'black'`으로 설정하세요.

[[[generic-javascript-create-variable]]]

\--- hints \--- \--- hint \--- 아래 코드를 파일 가장 위에 삽입하세요.

![스크린샷](images/pixel-art-pencolour.png) \--- / 귀뜸말 \--- \--- / 귀뜸말 \---

+ 변수 아래에 새 `setPenColour` 함수를 만들어서 `pen`의 색깔을 함수에서 받을 수 있도록 합니다. 아까 만들었던 `setPixelColour` 함수를 참고하시면 도움이 될 것입니다.

[[[generic-javascript-create-a-function]]]

+ `setPenColour` 함수에 아래 코드를 추가하여 `penColour` 변수가 `pen`의 색깔을 함수에서 입력으로 받을 수 있도록 합니다.

![<0>#outside-pic</0> CSS 코드에서 <0>width</0>(너비) 와 <0>height</0>(높이) 값을 수정하여, 바깥 쪽에 있는 이미지를 <0>200px</0>로 수정해보세요. (<0>px</0>는 픽셀을 의미합니다.)](images/pixel-art-set-pen.png)

또한 `penColour` 변수를 픽셀 색상을 바꿀 때 사용해야 합니다.

+ `setPixelColour` 함수를 아래와 같이 `black` 대신 `penColour`로 변경합니다.
    
    ![스크린샷](images/pixel-art-use-pen.png)

+ `index.html` 파일에서 아래 코드를 추가하여 팔레트의 색깔을 클릭하면 `setPenColour` 함수가 동작하도록 제작하십시오.

![스크린샷](images/pixel-art-palette-onclick.png)

+ 펜 색상이 검은색, 흰색으로 바뀌는지, 픽셀 색깔을 채우거나 삭제할 수 있는지 테스트해 보세요.