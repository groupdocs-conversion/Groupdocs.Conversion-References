---
title: "font_config_substitution_enabled प्रॉपर्टी"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "यह प्रॉपर्टी सिस्टम FontConfig के आधार पर अनुपलब्ध फ़ॉन्ट्स की स्वचालित प्रतिस्थापन को सक्षम करती है।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/
is_root: false
weight: 2110
---


## font_config_substitution_enabled property

यह प्रॉपर्टी सिस्टम FontConfig के आधार पर लापता फ़ॉन्ट्स के स्वचालित प्रतिस्थापन को सक्षम करती है। डिफ़ॉल्ट False है।

नोट: प्रतिस्थापन का क्रम इस प्रकार है:
- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_config_substitution_enabled(self):
    ...
@font_config_substitution_enabled.setter
def font_config_substitution_enabled(self, value):
    ...
```

### साथ ही देखें
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
