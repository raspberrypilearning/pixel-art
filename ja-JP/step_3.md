## ピクセルグリッドを作成する

ピクセルアートの作成に使用できるピクセルのグリッドを作成しましょう。

グリッドはテーブルのように見えます。表には行が含まれ、行にはピクセルを表すセルが含まれます。

+ [スターター小物](http://jumpto.cc/web-pixel)開きます。

プロジェクトはこのようになります。

![スクリーンショット](images/pixel-starter.png)

まず、黒い背景を持つテーブルを作成し、白いピクセルをそのテーブルに入れるコードを記述しましょう。

+ あなたの `index.html` ファイルの `<body>` にこのコードを追加して `<div>`：

![スクリーンショット](images/pixel-art-art.png)

`<div>` は不可視のボックスで、 **スタイルを与えることができます**。 この `<div>` にはID `art`があります。これにより、ボックスにスタイルを追加できるようになります。

+ 今度は `style.css` ファイルに行き、 `<div>` という `アート`のテーブルスタイリングを追加してください。

![スクリーンショット](images/pixel-art-style.png)

これにより、境界線を持つテーブルが作成され、グリッド内の間隔が設定されます。

それはまだ非常に面白そうに見えないので、内部にピクセルの行を配置する必要があります。

+ `index.html` ファイルに戻って、3つのピクセル **行を** の `アート` ボックスに追加します。 時間を節約したい場合は、最初の行を入力してからコピーして貼り付けて、他の行を作成することができます。

![スクリーンショット](images/pixel-art-row.png)

ここでは、IDの代わりに **クラス** を使用してdivをスタイルすることに注目してください。これはたくさんありそうなので、クラスがもっと便利です。

+ `style.css` ファイルに切り替えて、各行内の行とピクセルに次のスタイルを追加します。

![スクリーンショット](images/pixel-art-row-style.png)

これで、ピクセルがグリッド内に黒線で表示されます。

+ `index.html` ファイルに、別の2つのピクセルセクションを追加して、3×3ピクセルグリッドを作成します。もう一度コピー＆ペーストして時間を節約することができます。

\--- hints \---

\--- hint \---

Find the `<div>` tag with the class `row` and copy it, including the three rows labelled `pixel` which are inside it, up to and including its matching `</div>` tag.

Paste this code immediately below the section you just copied to create another row. Repeat once more so that you have three rows of three pixels each.

You can check whether your table looks right by looking at the result area on the right.

\--- /hint \---

\--- hint \---

Here is how your code should look:

![screenshot](images/pixel-art-grid-3.png)

\--- /hint \---

\--- /hints \---