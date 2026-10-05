---
title: "font_substitutes प्रॉपर्टी"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "WordProcessing दस्तावेज़ रूपांतरण के दौरान उपयोग किए जाने वाले फ़ॉन्ट प्रतिस्थापन।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/
is_root: false
weight: 2140
---


## font_substitutes property

WordProcessing दस्तावेज़ रूपांतरण के दौरान उपयोग किए जाने वाले फ़ॉन्ट प्रतिस्थापन।

नोट: प्रतिस्थापन का क्रम इस प्रकार है:

- 1) Automatically substitute missing fonts based on font name (if enabled).
- 2) Automatically substitute missing fonts based on FontConfig (if enabled).
- 3) Substitute missing fonts based on FontSubstitutes (if set).
- 4) Automatically substitute missing fonts based on FontInfo (if enabled).
- 5) Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_substitutes(self):
    ...
@font_substitutes.setter
def font_substitutes(self, value):
    ...
```

### साथ ही देखें
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
