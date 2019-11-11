## 为像素着色

该项目使用三种不同的语言：

+ HTML用于组织您的内容
+ CSS用于设定内容的样式
+ JavaScript 是一种编程语言。您可以用它来设定网页如何回复用戶的交互。

让我们添加一些JavaScript代码，在单击像素时可以自动为像素着色。

我们将创建一个**函数** 。 函数就是一个被命名了的，执行特定任务的代码块。 当我们想运行一个函数所包含的代码时，我们可以通过它的名字**调用**此函数。

+ 在` script.js`文件中，创建一个名称为` setPixelColour`的函数。 `setPixelColour`函数需要一个`像素`作为**输入**，函数就可以改变这个像素的颜色。

![创建函数](images/create-function.png)

+ 在函数中添加以下代码以设置像素的背景色：

![截屏](images/pixel-art-set-pixel-colour.png)

请注意，` backgroundColor `使用美国拼写。

目前，此代码没有任何作用。

+ 回到`index.html`文件，将以下代码添加到第一个像素上。当您点击这个像素时，就將调用`setPixelColour`函数：

![截屏](images/pixel-art-onclick.png)

括号中的`this`是` setPixelColour`函数的输入，它指定了要设置颜色的像素— ` this`！

+ 通过单击第一个像素来测试代码。它应该变成黑色。

![截屏](images/pixel-art-black.png)

您仅添加了` onclick `代码到第一个像素，因此点击其他像素将不会执行任何操作。