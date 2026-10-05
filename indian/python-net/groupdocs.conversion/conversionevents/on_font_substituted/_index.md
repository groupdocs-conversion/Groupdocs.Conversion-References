---
title: "on_font_substituted प्रॉपर्टी"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "इवेंट तब फायर होता है जब स्रोत दस्तावेज़ द्वारा संदर्भित फ़ॉन्ट उपलब्ध नहीं होता और उसे प्रतिस्थापित किया जाता है (या तो ग्राहक‑प्रदान किए गए FontSubstitute नियम द्वारा, कॉन्फ़िगर किए गए डिफ़ॉल्ट फ़ॉन्ट द्वारा, या द्वारा…"
type: docs
url: /hi/python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

जब स्रोत दस्तावेज़ द्वारा संदर्भित फ़ॉन्ट उपलब्ध नहीं होता और उसे प्रतिस्थापित किया जाता है (या तो ग्राहक‑प्रदानित [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) नियम द्वारा, कॉन्फ़िगर किए गए डिफ़ॉल्ट फ़ॉन्ट द्वारा, या परिवर्तन पाइपलाइन की आंतरिक फ़ॉलबैक द्वारा)।

इवेंट को प्रत्येक `(SourceFileName, OriginalFontName)` के आधार पर एकल `Converter.Convert(...)` कॉल के भीतर डिडुप्लिकेट किया जाता है — सब्सक्राइबर्स को प्रत्येक स्रोत दस्तावेज़ में हर गायब फ़ॉन्ट के लिए अधिकतम एक सूचना मिलती है। यह रूपांतरण थ्रेड पर सिंक्रोनस रूप से फायर होता है। इमेज रूपांतरणों के लिए नहीं उठाया जाता।

प्रेजेंटेशन दस्तावेज़ों के लिए, फ़ॉन्ट प्रतिस्थापन केवल Windows पर ही पता चलता है, क्योंकि इंजन इसे प्लेटफ़ॉर्म‑विशिष्ट फ़ॉन्ट मिलान के माध्यम से हल करता है जो अन्य ऑपरेटिंग सिस्टम पर उपलब्ध नहीं है।

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### साथ ही देखें
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
