## 创建像素网格

让我们创建一个你可以用于创建像素艺术的像素网格。

创建的网格看起来就像一个表格。表格包含行，而行则包含代表像素的单元格。

+ 启动[trinket](http://jumpto.cc/web-pixel){:target="http://jumpto.cc/web-pixel"}

项目如下图所示：

![截屏](images/pixel-starter.png)

首先，让我们写一些代码来创建一个带黑色背景的表格，然后在其中放入白色像素。

+ 将下面的代码添加到` index.html </0>文件的<body&gt</body&gt中，用以创建一 个<div&gt：</li>
</ul>

<p><img src="images/pixel-art-art.png" alt="截屏" /></p>

<p><div&gt是一个不可见的框，但是您可以给它设置一个<strong>样式</strong>。 创建的<div&gt的ID是 <code> art ` ，有了ID才可以设置样式。</p> 
    + 现在修改 `style.css` 文件，为 `art `添加表样式。
    
    ![截屏](images/pixel-art-style.png)
    
    这将创建一个带边框的表格，并设置好网格内的间距。
    
    暂时它看起来还不太有趣，因此您需要在行中放入像素。
    
    + 回到` index.html `文件并在 `art`框内添加三个同一行的像素。 如果要节省时间，可以键入第一行后，将其复制并粘贴用以创建其他行。
    
    ![截屏](images/pixel-art-row.png)
    
    请注意，在这里您使用的是**class**而不是ID来为div设置样式。在有很多重复的情況下，使用类会更方便。
    
    + 切回到` style.css `文件，为每行和每行中的像素添加以下样式：
    
    ![截屏](images/pixel-art-row-style.png)
    
    现在，您的像素将排列成网格，并且外围有一圈黑线。
    
    + 在` index.html中`文件中，添加另外两个像素区，创建出一個3×3像素网格。您可以再次使用复制和粘贴来节省时间。
    
    \--- hints \--- \--- hint \--- 找到包含有`声明row类的<code><div>`标记</code>后，从这里开始，一直复制到匹配的` </div>`标签，这其中包括标有` pixel的三行`。
    
    将此代码粘贴在您刚刚复制的部分下面以创建另一行。 再次重复，这样您就创建了三行，每行三个像素。
    
    您可以通过查看右侧的结果区域来检查表格是否正确。 /提示\--- \---提示\--- 这是代码的外观：
    
    ![截屏](images/pixel-art-grid-3.png) \--- /hint \--- \--- /hints \---