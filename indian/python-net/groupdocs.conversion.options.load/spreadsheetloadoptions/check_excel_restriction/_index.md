---
title: "check_excel_restriction प्रॉपर्टी"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "यह प्रॉपर्टी निर्धारित करती है कि क्या सेल-संबंधित वस्तुओं को संशोधित करते समय Excel फ़ाइल प्रतिबंधों की जाँच की जाती है।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

यह प्रॉपर्टी निर्धारित करती है कि क्या सेल-संबंधित वस्तुओं को संशोधित करते समय Excel फ़ाइल प्रतिबंधों की जाँच की जाती है।

यदि true है, तो 32 K से अधिक लंबी स्ट्रिंग इनपुट करने का प्रयास करने पर एक अपवाद उत्पन्न होगा। यदि false है, तो इनपुट स्ट्रिंग स्वीकार की जाएगी, जिससे पूर्ण मान को CSV जैसे अन्य फ़ॉर्मैट में आउटपुट किया जा सकेगा। हालांकि, ऐसी अमान्य मानों के साथ वर्कबुक को फिर से Excel फ़ॉर्मैट में सहेजने से अप्रत्याशित त्रुटियाँ हो सकती हैं।

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### साथ ही देखें
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
