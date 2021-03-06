## पिक्सेल का ग्रिड बनाएँ

अब पिक्सेल का एक ग्रिड बनाते हैं जिसका उपयोग आप पिक्सेल कला बनाने के लिए कर सकते हैं।

ग्रिड यह एक तालिका की तरह दिखेगा। तालिकाओं में पंक्तियाँ होती हैं, और पंक्तियों में जो कोशिकाएँ होती हैं वो पिक्सेल का प्रतिनिधित्व करती हैं।

+ [स्टार्टर ट्रिंकेट](http://jumpto.cc/web-pixel) खोलें।

प्रोजैक्ट इस तरह दिखनी चाहिए:

![स्क्रीनशॉट](images/pixel-starter.png)

सबसे पहले, एक काले रंग की पृष्ठभूमि के साथ एक तालिका बनाने के लिए कोड लिखें और फिर इसमें कुछ सफेद पिक्सेल डालें।

+ इस कोड को अपने `<body>` `index.html` फ़ाइल में जोड़ें: `<div>`

![स्क्रीनशॉट](images/pixel-art-art.png)

`<div>` एक अदृश्य बॉक्स है जिसमें आप एक **शैली** दे सकते हैं। इस `<div>` का आईडी `कला (art)` है, जो आपको चाहिए ताकि आप डिब्बे में शैलियों को जोड़ सकें।

+ अब अपनी `style.css` फ़ाइल पर जाएँ और तालिका शैली मे शैली जोड़ें जिसका `<div>` आईडी `कला (art)` है।

![स्क्रीनशॉट](images/pixel-art-style.png)

यह एक सीमा के साथ एक तालिका बनाता है और ग्रिड के अंदर अंतर जमाता है।

यह अभी तक बहुत दिलचस्प नहीं है, इसलिए आपको इसके अंदर पिक्सेल की पंक्तियाँ डालने की आवश्यकता है।

+ अपने `index.html` फ़ाइल पर वापस जाएं और **अंदर** तीन पिक्सेल की एक पंक्ति `कला (art)` डिब्बे के जोड़ें। यदि आप समय बचाना चाहते हैं, तो आप पहली पंक्ति लिख कर फिर इसे कॉपी और पेस्ट करके दूसरी पंक्ति बना सकते हैं।

![स्क्रीनशॉट](images/pixel-art-row.png)

ध्यान दें कि यहां आप आईडी के बजाय **कक्षा** का उपयोग div की शैली के लीये कर रहे हैं। यह इसलिए है क्योंकि एसे बहुत सारे होंगे, इसलिए एक कक्षा अधिक उपयोगी है।

+ फिर से `style.css` फ़ाइल खोले करें और प्रत्येक पंक्ति और पिक्सेल के लिए निम्न शैलियों को जोड़ें:

![स्क्रीनशॉट](images/pixel-art-row-style.png)

अब आपके पिक्सेल ग्रिड में उनके चारों ओर काली रेखाओं के साथ पंक्तिबद्ध होंगे।

+ अपने `index.html` फ़ाइल में, 3 × 3 पिक्सेल ग्रिड बनाने के लिए पिक्सेल के दो और खंड जोड़ें। समय बचाने के लिए आप कॉपी और पेस्ट का उपयोग कर सकते हैं।

--- hints ---


--- hint ---

टैग `<div>` ढूंढें जिसकि कक्षा `पंक्ति (row)` हो और इसे नकल करें. नकल मे `पिक्सेल (pixel)` लेबल वाली तीन पंक्तियाँ जो उसके अंदर हैं, और उसका मेल करता टैग `</div>` भी शामिल करे।

इस कोड को तुरंत उस अनुभाग के नीचे चिपकाइये जिसे आपने दूसरी पंक्ति बनाने के लिए नकल किया था। एक बार और दोहराएं ताकि आपके पास तीन पिक्सेल की तीन पंक्तियाँ हों।

आप जाँच सकते हैं कि आपकी तालिका सही पर परिणाम क्षेत्र को देखकर सही है या नहीं।

--- /hint ---

--- hint ---

यहाँ दिखाया गया है कि आपका कोड कैसा दिखेगा:

![स्क्रीनशॉट](images/pixel-art-grid-3.png)

--- /hint ---

--- /hints ---