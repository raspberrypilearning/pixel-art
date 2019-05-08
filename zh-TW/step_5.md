## 為像素著色

該項目使用三種不同的語言：

+ HTML用於組織您的內容
+ CSS告訴內容樣式的樣子
+ JavaScript是一種編程語言，可用於在與其進行交互時使網頁響應

當您單擊它時，讓我們自動添加一些JavaScript代碼以在像素中著色。

我們將創建一個 **函數**。 函數是命令執行特定任務的代碼塊。 我們可以 **通話** 的時候，我們要運行它包含的代碼，它的名字的功能。

+ 在 `script.js` 文件中，創建一個名為 `setPixelColour`的函數。 `setPixelColour` 函數需要將 `像素` 作為 **輸入** 以便它可以改變該像素的顏色。

![創建功能](images/create-function.png)

+ 在函數內添加此代碼以設置像素的背景顏色：

![截圖](images/pixel-art-set-pixel-colour.png)

請注意， `backgroundColor` 使用美國拼寫“color”。

目前這段代碼沒有任何效果。

+ 轉到 `index.html` 並將以下代碼添加到第一個像素，這樣當您單擊此像素時，將調用 `setPixelColour` 函數：

![截圖](images/pixel-art-onclick.png)

括號中的 `這` 是 `setPixelColour` 函數的輸入，它讓它知道哪個像素設置顏色 - `這個` 像素！

+ 單擊第一個像素測試代碼。它應該變成黑色。

![截圖](images/pixel-art-black.png)

你只添加了 `onclick` 代碼到 **前** 像素，所以點擊其他像素將不會做任何事情。