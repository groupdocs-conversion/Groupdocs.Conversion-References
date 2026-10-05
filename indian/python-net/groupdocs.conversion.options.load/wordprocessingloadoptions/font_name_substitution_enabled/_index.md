---
title: "font_name_substitution_enabled प्रॉपर्टी"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "यह प्रॉपर्टी दर्शाती है कि क्या गायब फ़ॉन्ट्स को फ़ॉन्ट नाम के आधार पर स्वचालित रूप से प्रतिस्थापित किया जाता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/
is_root: false
weight: 2130
---


## font_name_substitution_enabled property

यह प्रॉपर्टी दर्शाती है कि क्या लापता फ़ॉन्ट्स फ़ॉन्ट नाम के आधार पर स्वचालित रूप से प्रतिस्थापित किए जाते हैं। डिफ़ॉल्ट: False।

नोट: प्रतिस्थापन का क्रम इस प्रकार है:

- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_name_substitution_enabled(self):
    ...
@font_name_substitution_enabled.setter
def font_name_substitution_enabled(self, value):
    ...
```

### साथ ही देखें
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
