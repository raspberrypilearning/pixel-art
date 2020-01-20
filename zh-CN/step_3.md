## 创建像素网格

让我们创建一个你可以用于创建像素艺术的像素网格。

创建的网格看起来就像一个表格。表格包含行，而行则包含代表像素的单元格。

+ 启动[trinket](http://jumpto.cc/web-pixel)

项目如下图所示：

![截屏](images/pixel-starter.png)

首先，让我们写一些代码来创建一个带黑色背景的表格，然后在其中放入白色像素。

+ 将下面的代码添加到` index.html `文件的`<body>`中，用以创建一个`<div>`：

![截屏](images/pixel-art-art.png)

`<div>`是一个不可见的框，您可以为其赋予**样式** 。 创建的`<div>`的ID是 `art` ，有了ID才可以设置样式。

+ 现在转到你的 `style.css` 文件，为名叫 `art `的`<div>`添加表样式。

![截屏](images/pixel-art-style.png)

这将创建一个带边框的表格，并设置好网格内的间距。

暂时它看起来还不太有趣，因此您需要在其中放入一行一行的像素。

+ 回到` index.html `文件，并在 `art`**框内**添加三个同一行的像素。 如果要节省时间，可以在输入第一行后，将其复制并粘贴用来创建其他行。

![截屏](images/pixel-art-row.png)

请注意，在这里您使用的是**class**而不是ID来为div设置样式。在有很多重复的情况下，使用class（类）会更方便。

+ 切回到` style.css `文件，为每行和每行中的像素添加以下样式：

![截屏](images/pixel-art-row-style.png)

现在，您的像素将排列成网格，并且外围有一圈黑线。

+ 在` index.html中`文件中，添加另外两个像素区，创建出一个3×3的像素网格。您可以再次使用复制和粘贴来节省时间。

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