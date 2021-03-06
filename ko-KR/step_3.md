## 픽셀 그리드 만들기

픽셀 아트를 만들 때 사용할 픽셀 그리드를 만들어 봅시다.

그리드는 우리가 흔히 보는 표처럼, 행과 셀로 표현되어 있습니다.

+ 이 [trinket](http://jumpto.cc/web-pixel)을 열어 주십시오.

프로젝트는 아래와 같이 보일 것입니다:

![스크린샷](images/pixel-starter.png)

먼저 검정색 배경이 있는 표를 만들고, 흰색 픽셀을 그 안에 넣는 코드를 작성해 보겠습니다.

+ `<div>`를 만들기 위해 아래 코드를 `index.html`의 `<body>`에 넣어주세요.

![스크린샷](images/pixel-art-art.png)

`<div>` 태그는 보이지 않는 박스이나, **스타일을 지정할 수 있습니다.** `<div>`은 `art`라는 ID를 가지고 있습니다. 이 영역에 스타일을 추가할 수 있는 것입니다.

+ 이제 `style.css` 파일로 이동하여 `<div>` 내 `art`을 스타일링할 수 있는 코드를 추가하십시오.

![스크린샷](images/pixel-art-style.png)

이렇게 하면 태두리가 있는 표가 만들어지고 표 안의 간격이 설정됩니다.

아직 별로 흥미롭게 보이지 않네요, 그래서 내부에 픽셀 행을 넣어야 합니다.

+ `index.html` 파일로 돌아가 `art` 박스 **안에** 아래 3줄 코드를 추가해 봅시다. 만약 시간을 절약하고 싶다면 첫 번째 줄 코드를 입력한 다음에 복사 붙여넣기하는 방법이 있습니다.

![스크린샷](images/pixel-art-row.png)

여기서 **클래스**를 ID 대신 사용하고 있음을 주목하십시오. 많은 내용을 한번에 바꾸기 위해서는 클래스를 사용하는 것이 유용합니다.

+ `style.css` 파일로 돌아가 아래 코드를 추가하여, 각 행과 각 픽셀에 스타일을 추가합니다.

![스크린샷](images/pixel-art-row-style.png)

이제 픽셀 주위에 검은 선으로 된 눈금 선이 나타날 것입니다.

+ `index.html` 파일에서, 두 개의 픽셀 섹션을 추가하여 3x3 픽셀 격자를 만들어 보십시오. 복사 붙여넣기를 사용해서 시간을 절약할 수 있습니다.

--- hints ---



--- hint ---

`<div>`의 `row` 클래스를 찾아, `pixel`로 클래스와 같이 내용을 복사하세요. 코드가 올바르게 입력되도록 `</div>` 태그도 같이 복사하세요.

다른 행을 만들기 위해서는 방금 복사한 섹션 바로 아래에 코드를 붙여 넣으세요. 한번 더 반복하여 각각 3x3 픽셀을 만들어 봅시다.

오른쪽의 결과 영역을 보면 테이블이 올바르게 보이는지 확인할 수 있습니다.

--- /hint ---

--- hint ---

코드는 다음과 같이 설계되어야 합니다:

![스크린샷](images/pixel-art-grid-3.png)

--- /hint ---

--- /hints ---