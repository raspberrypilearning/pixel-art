## पिक्सेल को रंग करें

यह परियोजना तीन अलग-अलग प्रोग्रामिंग भाषाओं का उपयोग करती है:

+ HTML का उपयोग आपकी सामग्री को संगठित करने के लिए किया जाता है
+ सीएसएस सामग्री को बताता है कि शैलियों के साथ क्या देखना है
+ जावास्क्रिप्ट एक प्रोग्रामिंग भाषा है जिसका उपयोग कर आप वेबपेज से जवाब दे सकते हैं जब आप इस वेबपेज के साथ बातचीत करते हैं

अब कुछ जावास्क्रिप्ट कोड जोड़ते हैं जिससे पिक्सेल में रंग अपने आप से भर जाए जब आप उस पर क्लिक करते हैं।

हम एक ** फ़ंक्शन ** बनाएंगे। फ़ंक्शंस नामांकित कोड के खंड होते है जो एक विशेष कार्य करते हैं। हम फंक्शन को उसके नाम से **बुला** सकते हैं जब हम उसके कोड को चलाना चाहते हैं।

+ `script.js` फ़ाइल के अंदर एक फ़ंक्शन बनाएं जिसका नाम हो ` setPixelColour`। ` setPixelColour ` फ़ंक्शन को एक ` पिक्सेल `** इनपुट ** के रूप में लेने की आश्यकता है ताकि यह उस पिक्सेल का रंग बदल सके।

![Create function](images/create-function.png)

+ Add this code inside the function to set the background colour of the pixel:

![screenshot](images/pixel-art-set-pixel-colour.png)

Notice that `backgroundColor` uses the American spelling of 'colour'.

At the moment this code doesn't have any effect.

+ Go to `index.html` and add the following code to the first pixel so that when you click on this pixel, the `setPixelColour` function is called:

![screenshot](images/pixel-art-onclick.png)

The `this` in the brackets is the input for the `setPixelColour` function, which lets it know which pixel to set the colour for — `this` pixel!

+ Test your code by clicking on the first pixel. It should turn black.

![screenshot](images/pixel-art-black.png)

You've only added `onclick` code to the **first** pixel, so clicking on the other pixels won't do anything yet.