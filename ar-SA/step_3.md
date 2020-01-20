## إنشاء شبكة من وحدات البكسل

لننشئ شبكة من وحدات البكسل التي يمكنك استخدامها لإنشاء فن البكسل.

ستأخذ الشبكة شكل جدول من صفوف وأعمدة مكونة من خلايا تمثل وحدات البكسل.

+ افتح [مشغِّل trinket](http://jumpto.cc/web-pixel).

سيكون المشروع بالشكل التالي:

![لقطة الشاشة](images/pixel-starter.png)

لنكتب أولًا بعض التعليمات البرمجية لإنشاء جدول ذي خلفية سوداء ثم نضع فيه وحدات بكسل بيضاء.

+ أضف هذه التعليمة البرمجية داخل وسم `<body>` في الملف `index.html` لإنشاء وسم `<div>`:

![لقطة الشاشة](images/pixel-art-art.png)

يكون الوسم `<div>` مربعًا غير مرئي ويمكنك أن تحدِّد **نمطًا له**. ويتضمن هذا الوسمُ `<div>` المعرِّفَ `art` الذي ستحتاج إليه لتضيف أنماطًا إلى المربع.

+ انتقل الآن إلى الملف `style.css` وأضف نمط الجدول إلى الوسم `<div>` المُعرَّف بـ `art`.

![لقطة الشاشة](images/pixel-art-style.png)

سيؤدي ذلك إلى إنشاء جدول ذي حد وتعيين التباعد داخل الشبكة.

لا يبدو الجدول مثيراً للاهتمام حتى الآن، لذا فإنك تحتاج إلى وضع صفوف من وحدات البكسل داخله.

+ انتقل إلى ملف `index.html` وأضف صفًا مكونًا من ثلاث وحدات بكسل **داخل** المربع `art`. وإذا كنتَ تريد توفير الوقت، يمكنك إدخال الصف الأول ثم نسخه ولصقه لإنشاء صفوف أخرى.

![لقطة الشاشة](images/pixel-art-row.png)

لاحظ أنك تستخدم **class** بدلًا من ID لتحديد نمط أوسمة div. وهذا لأنه سيكون لديك الكثير من هذه الأوسمة، لذا سيكون استخدام class أكثر فائدة هنا.

+ انتقل إلى الملف `style.css` وأضف الأنماط التالية إلى الصفوف ووحدات البكسل داخل كل صف:

![لقطة الشاشة](images/pixel-art-row-style.png)

الآن ستصطف وحدات البكسل داخل شبكة تحيط بها خطوط سوداء.

+ في الملف `index.html`، أضف قسمين آخرين من وحدات البكسل لإنشاء شبكة 3×3. يمكنك استخدام النسخ واللصق مرة أخرى لتوفير الوقت.

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