---
title: "cap_resolution_to_page_content प्रॉपर्टी"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "यह प्रॉपर्टी प्रति-पृष्ठ PDF रेंडर रिज़ॉल्यूशन को पृष्ठ की मूल रास्टर रिज़ॉल्यूशन तक सीमित करती है, जिससे एम्बेडेड छवि से अधिक DPI पर रेंडरिंग रोकती है और पृष्ठ को उसकी मूल (छोटी) रिज़ॉल्यूशन पर जारी करती है…"
type: docs
url: /hi/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

यह प्रॉपर्टी प्रति-पृष्ठ PDF रेंडर रिज़ॉल्यूशन को पृष्ठ के मूल रास्टर रिज़ॉल्यूशन तक सीमित करती है, जिससे एम्बेडेड छवि से अधिक DPI पर रेंडरिंग रोकती है और अंतिम आउटपुट में पृष्ठ को उसके मूल (छोटे) पिक्सेल आयाम और DPI पर उत्पन्न करती है।

केवल इमेज‑प्रधान (स्कैन) पृष्ठ प्रभावित होते हैं; टेक्स्ट या वेक्टर सामग्री वाले पृष्ठ कभी भी सॉफ़्ट नहीं किए जाते और अनुरोधित DPI पर जारी किए जाते हैं। जब स्पष्ट आउटपुट [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) या [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) सेट किया जाता है, तो यह सीमा अनदेखी कर दी जाती है। डिफ़ॉल्ट False है (कोई सीमा नहीं; प्रत्येक पृष्ठ को अनुरोधित DPI पर रेंडर और जारी किया जाता है)।

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### साथ ही देखें
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
