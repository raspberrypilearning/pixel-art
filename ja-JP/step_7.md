## カラーパレットを追加する

なにか間違ってた場合、ピクセルの色を白に戻せないのは不便だと思いませんでしたか？ クリックでペンの色を選択できるように、カラーパレットを作成して修正しましょう。

+ このコードを `style.css` ファイルの末尾に追加して、ペンスタイルを作成します。

![スクリーンショット](images/pixel-art-pen.png)

+ それでは、さっき作成したペンスタイルを使用して黒と白のペンカラーでパレットを作成します。次のコードを`index.html`の `<body>` タグの下に追加して下さい:

![スクリーンショット](images/pixel-art-palette.png)

`style=` でHTMLファイルの中にCSSコードを追加することが出来ます。

パレットの色の1つをクリックすると、ペンの色が変わるようにコードを追加する必要があります。

+ `script.js` に切り替えて、ファイルの一番上に `penColour` という変数を作成します。その変数の値を `'black'`設定します。

[[[generic-javascript-create-variable]]]

--- hints ---


--- hint ---

ファイルの先頭に、次のコードを追加します。

![スクリーンショット](images/pixel-art-pencolour.png)

--- /hint ---

--- /hints ---

+ 変数の下に、`ペン (pen)`の入力を受け取る `setPenColour` という新しい関数を作成します。すでに作成した関数 `setPixelColour` を見てください。

[[[generic-javascript-create-a-function]]]

+ `setPenColour` 関数の中に、 `penColour` 変数を入力の `pen` 色に設定するコードを追加します。

![スクリーンショット](images/pixel-art-set-pen.png)

ピクセルの色を変更する場合は、 `penColor` 変数を使用する必要があります。

+ `black`の代わりに、`setPixelColour` 関数に変更して`penColour`変数を使います:
    
    ![スクリーンショット](images/pixel-art-use-pen.png)

+ `index.html` ファイルで、パレットの色をクリックしたときに `setPenColour` 関数を呼び出すコードを追加します。

![スクリーンショット](images/pixel-art-palette-onclick.png)

+ ペンの色を黒と白の間で切り替えて、ピクセルを塗りつぶしたり削除したりできることをテストします。