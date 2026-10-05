---
title: "detect_numbering_with_whitespaces प्रॉपर्टी"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "यह प्रॉपर्टी निर्धारित करती है कि प्लेन टेक्स्ट दस्तावेज़ के परिवर्तन के समय क्रमांकित सूची आइटम कैसे पहचाने जाते हैं।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

यह प्रॉपर्टी निर्दिष्ट करती है कि सादा पाठ दस्तावेज़ के रूपांतरण पर क्रमांकित सूची आइटम कैसे पहचाने जाते हैं। डिफ़ॉल्ट मान True है।

यदि यह विकल्प False पर सेट किया जाता है, तो सूची पहचान एल्गोरिद्म सूची पैराग्राफ़ को तब पहचानता है जब सूची संख्याएँ डॉट, राइट ब्रैकेट, या बुलेट प्रतीकों (जैसे "•", "*", "-" या "o") में समाप्त होती हैं।

यदि यह विकल्प True पर सेट किया जाता है, तो व्हाइटस्पेस भी सूची संख्या डिलिमिटर के रूप में उपयोग होते हैं: अरबी‑स्टाइल नंबरिंग (जैसे 1., 1.1.2.) के लिए सूची पहचान एल्गोरिद्म व्हाइटस्पेस और डॉट (".") दोनों प्रतीकों का उपयोग करता है।

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### साथ ही देखें
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
