## पिक्सेलचा ग्रिड तयार करा

पिक्सेल आर्ट तयार करण्यासाठी लागणाऱ्या पिक्सेलचा ग्रिड तयार करा.

ग्रीड टेबल सारखे दिसेल. टेबलमध्ये पंक्ती असतात आणि पंक्तींमध्ये चौकोनी डब्बे असतात जे पिक्सेलचे प्रतिनिधित्व करतात.

+ [starter trinket](http://jumpto.cc/web-pixel) उघडा.

प्रकल्प यासारखा दिसायला हवा:

![screenshot](images/pixel-starter.png)

प्रथम, काळ्या पार्श्वभूमीसह एक टेबल तयार करण्यासाठी काही कोड लिहू आणि त्यामध्ये पांढरे पिक्सेल ठेवू.

+ `<body>` च्या आत `index.html` फाईल मध्ये `<div>` टॅग तयार करण्यासाठी कोड जोडा:

![screenshot](images/pixel-art-art.png)

`<div>` एक अदृश्य बॉक्स आहे ज्यास तुम्ही **style** (शैली) देऊ शकता. या `<div>` मध्ये `art` id आहे, ज्याची तुम्हाला आवश्यकता आहे जेणेकरून तुम्ही बॉक्समध्ये styles जोडू शकता.

+ आता तुमच्या `style.css` फाईलवर जा आणि `art` नावाच्या `<div>` साठी टेबल style जोडा.

![screenshot](images/pixel-art-style.png)

हे बॉर्डरसोबत एक टेबल तयार करते आणि ग्रीडमध्ये अंतर सेट करते.

हे अजूनतरी फारसे चांगले दिसत नाही, म्हणून त्यामध्ये तुम्हाला पिक्सेलच्या पंक्ती जोडण्याची आवश्यकता आहे.

+ तुम्ही `index.html` फाईलवर परत जा आणि तीन पिक्सेलच्या पंक्ती `art` बॉक्सच्या **inside** (आतमध्ये) जोडा. तुमचा वेळ वाचवण्यासाठी, तुम्ही प्रथम पंक्ती टाइप करा आणि नंतर कॉपी आणि पेस्ट करू शकता.

![screenshot](images/pixel-art-row.png)

लक्षात घ्या की तुम्ही divs style करण्यासाठी येथे id ऐवजी **class** वापरत आहात कारण class वापराने जास्त उपयोगी आहे.

+ `style.css` वर स्विच करा प्रत्येक पंक्तीमध्ये पंक्ती आणि पिक्सेलसाठी खालील style जोडा:

![screenshot](images/pixel-art-row-style.png)

आता तुमचे पिक्सेल त्यांच्याभोवती काळ्या रेखा असलेल्या ग्रीडमध्ये असतील.

+ तुमच्या `index.html` फाइलमध्ये, 3 × 3 पिक्सेल ग्रिड तयार करण्यासाठी पिक्सलचे आणखी दोन विभाग जोडा. वेळ वाचवण्यासाठी तुम्ही पुन्हा कॉपी आणि पेस्ट वापरू शकता.

--- hints ---


--- hint ---

`<div>` टॅग ज्याचा क्लास `row` असेल ज्यामध्ये `pixel` लेबलच्या तीन पंक्तींसह जे त्याच्या आत असेल ते कॉपी करा, जोपर्यंत `</div>` टॅग सापडणार नाही.

तुम्हाला दुसरी कॉपी तयार करण्यासाठी नुकताच कॉपी केलेला कोड विभागाखाली पेस्ट करा. पुन्हा एकदा कोड कॉपी करा जेणेकरून तुमच्याकडे प्रत्येकी तीन पिक्सेलच्या तीन पंक्ती असतील.

उजवीकडील निकाल क्षेत्र पाहून तुमचे टेबल योग्य दिसत आहे की नाही ते तुम्ही तपासू शकता.

--- /hint ---

--- hint ---

तुमचा कोड कसा दिसला पाहिजे हे येथे आहे:

![screenshot](images/pixel-art-grid-3.png)

--- /hint ---

--- /hints ---