## 為像素塗上顏色

此項目使用三種不同的語言：

+ HTML用來整理你的內容
+ CSS用來定義樣式
+ JavaScript是一種程式語言，用於製作使用者互動時的網頁響應(回饋)

讓我們新增一些JavaScript程式碼, 用點擊來自動將一個像素塗上顏色。

我們將建立一個 **function**(函數)。 函數是執行特定任務的程式碼區塊。 我們可以 **call (呼叫)** 一個函數來執行它的程式碼。

+ 在 `script.js` 文件中，建立一個名為 `setPixelColour`的函數。 `setPixelColour` 函數需要將 `pixel` 作為一個 **input** 以便更改像素的顏色。

![新增函數](images/create-function.png)

+ 在此函數內添加此程式碼以設定像素的背景顏色：

![螢幕截圖](images/pixel-art-set-pixel-colour.png)

請注意，`backgroundColor` 使用美式拼法，“color”。

目前這段程式碼並沒有任何功能。

+ 到 `index.html` 並將以下程式碼添加到第一個像素，這樣當你點擊此像素時，將會呼叫 `setPixelColour` 函數：

![螢幕截圖](images/pixel-art-onclick.png)

括號中的 `this` 是 `setPixelColour` 函數的輸入，讓程式知道為哪個像素設置顏色 - `this` 像素！

+ 透過點擊第一個像素來測試你的程式碼。它應該變成黑色。

![螢幕截圖](images/pixel-art-black.png)

你目前只新增了 `onclick` 程式碼到 **first** 第一個像素，所以點擊其他像素將不會有任何效果。