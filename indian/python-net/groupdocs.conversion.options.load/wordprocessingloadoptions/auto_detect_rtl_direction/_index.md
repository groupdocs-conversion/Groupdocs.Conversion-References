---
title: "auto_detect_rtl_direction प्रॉपर्टी"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "autodetectrtldirection प्रॉपर्टी निर्धारित करती है कि क्या पैराग्राफ़ और रन, जिनमें मुख्यतः दाएँ‑से‑बाएँ पाठ है, रूपांतरण से पहले उनके बिडी फ़्लैग्स को ठीक किया जाए।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/
is_root: false
weight: 2010
---


## auto_detect_rtl_direction property

auto_detect_rtl_direction प्रॉपर्टी निर्धारित करती है कि क्या पैराग्राफ़ और रन, जिनमें मुख्यतः दाएँ‑से‑बाएँ पाठ है, रूपांतरण से पहले उनके बिडी फ़्लैग्स को ठीक किया जाता है।

जब इसे True (डिफ़ॉल्ट) पर सेट किया जाता है, तो यह प्रॉपर्टी Microsoft Word और LibreOffice द्वारा उपयोग की जाने वाली एक ह्यूरिस्टिक लागू करती है, जिससे Google Docs जैसे टूल्स द्वारा उत्पन्न अरबी/हिब्रू दस्तावेज़ों की रेंडरिंग ठीक होती है, जो OOXML को <w:bidi/> के बिना और केवल RTL स्क्रिप्ट वाले रन पर <w:rtl w:val="0"/> के साथ उत्पन्न करते हैं। इसे False पर सेट करने से स्रोत मार्कअप की सख्त OOXML व्याख्या बनी रहती है।

### Definition:
```python
@property
def auto_detect_rtl_direction(self):
    ...
@auto_detect_rtl_direction.setter
def auto_detect_rtl_direction(self, value):
    ...
```

### साथ ही देखें
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
