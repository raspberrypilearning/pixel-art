## 添加調色板

如果你犯了錯誤，你是否覺得難以將像素的顏色改回白色？ 讓我們通過創建調色板來解決這個問題，以便您可以通過單擊選擇筆顏色。

+ 在 `style.css` 文件的底部添加此代碼以創建筆樣式：

![截圖](images/pixel-art-pen.png)

+ 現在使用剛創建的筆樣創建一個黑白筆顏色的調色板。將以下代碼添加到 `<body>` 標記下面的 `index.html`：

![截圖](images/pixel-art-palette.png)

`style =` 允許您在HTML文件中添加CSS代碼，這在這裡很方便。

我們需要添加代碼，以便在單擊調色板中的一種顏色時，筆的顏色會發生變化。

+ 切換到 `script.js` 並在文件的最頂部創建一個名為 `penColour` 的變量。該變量的值設置為 `“黑色”`。

[[[generic-javascript-create-variable]]]

\---提示\--- \---提示\--- 在文件頂部添加以下代碼：

![截圖](images/pixel-art-pencolour.png) \--- /提示\--- \--- /提示\---

+ 在變量下面，創建一個名為 `setPenColour` 的新函數，輸入為 `筆`。查看您已創建的功能 `setPixelColour` 來幫助您。

[[[generic-javascript-create-a-function]]]

+ 在 `setPenColour` 函數內，添加代碼以將 `penColour` 變量設置為作為輸入提供的 `筆` 顏色。

![截圖](images/pixel-art-set-pen.png)

更改像素的顏色時，還需要使用 `penColour` 變量。

+ 更改 `setPixelColour` 函數以使用 `penColour` 變量而不是 `black`：
    
    ![截圖](images/pixel-art-use-pen.png)

+ 在 `index.html` 文件中，添加一些代碼以在單擊調色板中的顏色時調用 `setPenColour` 函數。

![截圖](images/pixel-art-palette-onclick.png)

+ 測試您可以在黑白之間切換筆顏色以填充或刪除像素。