---
description: मैनुअल पढ़ें
---

# 🛠 सेटअप करना

अगर आपको कोई त्रुटियाँ महसूस होती हैं, तो [FAQ](faq.md) पर जाएँ।

सेटअप करने से पहले, सुनिश्चित करें कि आपके पास एक स्थानिक डिस्कॉर्ड क्लाइंट (**ब्राउज़र में नहीं**) है और डिस्कॉर्ड सेटिंग्स में गतिविधि स्थिति को सक्षम कर दिया है:

![छवि](https://github-production-user-asset-6210df.s3.amazonaws.com/91019667/263746610-4e5579d4-5bed-4742-8bc7-9d033461ed42.png)

## सेटअप प्रक्रिया

* [https://discord.com/developers/applications/](https://discord.com/developers/applications/) पर जाएँ।
* ऊपरी दाएँ कोने में **नई एप्लिकेशन** पर क्लिक करें।

![छवि](https://github-production-user-asset-6210df.s3.amazonaws.com/91019667/263747106-b06bb1c4-2544-4e59-ac6b-231a38091517.png)

* एप्लिकेशन के लिए एक नाम चुनें, यह स्थिति में "Playing" के बाद प्रदर्शित होगा; **बनाएँ** पर क्लिक करें।
* **एप्लिकेशन आईडी** की प्रतिलिपि बनाएँ और उसे कस्टम आरपी फ़ील्ड **आईडी** में पेस्ट करें, फिर **कनेक्ट** पर क्लिक करें। सही तरीके से किया जाता है तो अब आपकी डिस्कॉर्ड में स्थिति "Playing **\[एप्लिकेशन का नाम]**" कहेगी।
  * नोट: अगर आपने पहले से ही कस्टम स्थिति सेट की है (वह जिसमें इमोजी होता है), तो वह आपके CustomRP स्थिति के ऊपर प्राथमिकता देगा। यह प्रोफ़ाइल पॉपअप में दिखाया जाएगा हालांकि।


![छवि](https://github-production-user-asset-6210df.s3.amazonaws.com/91019667/263748037-1aa823d9-9d73-415d-8070-a39153e83aa9.png)

* आपके एप्लिकेशन के पृष्ठ पर, Rich Presence -> Art Assets में जाएँ और अगर आप उन्हें उपयोग करना चाहते हैं तो कम से कम एक छवि को Rich Presence Assets के तहत अपलोड करें। CustomRP में, फ़ाइल मेनू में एक सुविधाजनक **एसेट्स अपलोड करें** बटन होता है (आप Ctrl+U भी उपयोग कर सकते हैं) जो आपको वहां ले जाएगा अगर आपकी आईडी फ़ील्ड सही ढंग से सेटअप की है।
  * वैकल्पिक रूप से, आप छवि के लिए सीधा लिंक डाल सकते हैं **कुंजी** फ़ील्ड में।
  * नोट: जब आप अपने उपस्थिति में बटन पर क्लिक करेंगे, तो वे काम नहीं करेंगे, लेकिन चिंता न करें, वे दूसरों के लिए काम करेंगे। यह डिस्कॉर्ड की ओर से एक समस्या है।
* अपने एप्लिकेशन के पृष्ठ पर जाकर, फ़ील्ड **State, Details, Large Image Key, Large Image Text, Small Image Key, Small Image Text, Party Size, Party Max** को सेटअप करें। ये सभी वैकल्पिक हैं।
* जब आपने वह सेटअप पाया हो, तो उन मूल्यों की प्रतिलिपि CustomRP के समर्पित फ़ील्ड में करें।
  * सुझाव: आप एप्लिकेशन में लगभग किसी भी नियंत्रण पर हवा में उड़ने के लिए ले जा सकते हैं (लेबल्स की तरह **Details**) और यह आपको एक टूलटिप देगा!
* अगर आप बटन सेटअप करना चाहते हैं, तो उसमें दोनों पाठ और URL फ़ील्ड भरें।
  * नोट: जब आप अपनी खुद की उपस्थिति में बटन पर क्लिक करेंगे, तो वे काम नहीं करेंगे, लेकिन चिंता न करें, वे दूसरों के लिए काम करेंगे। यह डिस्कॉर्ड की ओर से एक समस्या है।
* **अपडेट प्रासेंस** (या यदि आप पहले से कनेक्ट नहीं हैं तो **कनेक्ट** पर क्लिक करें)।
* बधाई हो, आप महान हैं!

### मैं एक से ज़्यादा डिस्कॉर्ड क्लाइंट उपयोग करता हूँ, मुझे क्या करना चाहिए?

अगर आपके पास एक से ज़्यादा डिस्कॉर्ड क्लाइंट हैं और आप चाहते हैं कि आपकी उपस्थिति एक ऐसे खाते पर दिखाई दे जो एप्लिकेशन ने स्वचालित रूप से चुना नहीं, तो कृपया **डिस्कनेक्ट करें** पर क्लिक करें, फिर अपने कीबोर्ड पर Ctrl+Shift दबाएं और **कनेक्ट** पर क्लिक करें। एक नंबर इनपुट वाली विंडो आएगी, उसमें एक नंबर 1 डालें, विंडो को बंद करें, और बिना Ctrl+Shift के फिर से **कनेक्ट** पर क्लिक करें। अगर यह फिर से गलत खाता है, तो 0, फिर 2 और आगे बढ़ते रहें।

कृपया ध्यान दें कि अगर आपके पास बूट से बूट तक कई डिस्कॉर्ड क्लाइंट चलते हैं, तो प्रत्येक क्लाइंट के लिए पाइप नंबर प्रतिस्थानिक नहीं हो सकता है और यह इस पर निर्भर कर सकता है कि कौन सा क्लाइंट पहले शुरू हुआ। ऐसे बचने के लिए, आप या तो अतिरिक्त क्लाइंट को मैन्युअल रूप से शुरू कर सकते हैं, या विंडोज टास्क स्केड्यूलर का उपयोग करके क्लाइंट के स्टार्टअप को विलंबित कर सकते हैं।

अगर आप एक समय में 2 खाते उपयोग करते हैं और चाहते हैं कि हर एक का अलग प्रेज़न्स हो, तो निम्नलिखित कदमों का पालन करें:

* सबसे पहले अपने मुख्य खाते को उपरोक्त निर्देशों के साथ सेटअप करें।
* CustomRP के नवीनतम **पोर्टेबल (.zip)** संस्करण को प्राप्त करें (वेबसाइट से [https://www.customrp.xyz](https://www.customrp.xyz) या [गिटहब रिलीज़ पेज](https://github.com/maximmax42/Discord-CustomRP/releases/latest)) और उसे किसी भी स्थान पर अनपैक करें।
  * यह केवल संस्करण 1.16 और पुराने संस्करणों के साथ काम करता है।
* `Start Second Instance.bat` खोलें या CustomRP.exe के लिए एक शॉर्टकट बनाएं और उसे एक तर्क `--second-instance` (या `-2`) के साथ।
* प्रोग्राम को मुख्य तरीके से सेटअप करें जैसे कि आपने मुख्य इंस्टेंस को किया था।
  * सुझाव: यदि आपके पास पहले से ही एक प्रीसेट है जिसे आप दूसरे इंस्टेंस के साथ उपयोग करना चाहेंगे, तो आप बैट फ़ाइल को संपादित कर सकते हैं या शॉर्टकट को संशोधित कर सकते हैं ताकि प्रेस्ट के पथ को शामिल किया जा सके। उदाहरण: `CustomRP.exe -2 "C:\Some Folder\preset.crp"` (यदि पथ में स्थान हो, तो पथ के चारों ओर उद्धरण चिन्ह आवश्यक हैं)।
* कनेक्ट करने से पहले, ऊपर वर्णित तरीके से पाइप को बदलें और कनेक्ट करें।

यदि आप एक समय में 3 या उससे अधिक खाते उपयोग करते हैं, तो... आपके पर्याप्त आलोचना में, मैं अधिक इंस्टेंस के लिए समर्थन जोड़ने के लिए समर्थ हो जाऊँगा।

## नोट्स

* यदि आप छोटी या बड़ी छवि सेट नहीं करना चाहते हैं, तो कृपया कार्यक्रम में सभी संबंधित फ़ील्ड को खाली छोड़ दें।
* यदि बड़ी छवि सेट नहीं है, तो छोटी छवि सेटिंग्स को अनदेखा किया जाएगा।