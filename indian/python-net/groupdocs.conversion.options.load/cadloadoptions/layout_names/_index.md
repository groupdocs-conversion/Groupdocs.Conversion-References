---
title: "layout_names प्रॉपर्टी"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "परिवर्तित किए जाने वाले लेआउट नाम।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/
is_root: false
weight: 2060
---


## layout_names property

परिवर्तित किए जाने वाले लेआउट नाम।

PDF/UA-1 में कनवर्ट करते समय यह सम्मानित नहीं होता। वह लक्ष्य ड्राइंग को एकल टैग्ड पेज के रूप में रेंडर करता है, जो चयनित लेआउट प्रति एक शीट नहीं ले जा सकता, इसलिए पूरी ड्राइंग को बदले में कनवर्ट किया जाता है और यहाँ कुछ भी लागू नहीं होता।

PDF सहित सभी अन्य लक्ष्य चयन का सम्मान करते हैं। उन लक्ष्यों पर, नाम ड्राइंग द्वारा रखे गए लेआउट्स के विरुद्ध बिल्कुल मिलते हैं, इसलिए केवल केस में अंतर वाला नाम अलग नाम माना जाता है। ऐसा नाम जो कुछ भी नहीं मिलाता, उसे हटा दिया जाता है और कॉलर को केवल वह शीट ही लागत है; ऐसी सूची जिसमें कुछ भी नहीं मिलता, वह `InvalidLoadOptionsException` के साथ कनवर्ज़न को फेल कर देती है, जिसमें मिस हुए नाम और ड्राइंग द्वारा रखे गए लेआउट्स का उल्लेख होता है, बजाय उन शीट्स को रेंडर करने के जो कॉलर ने नहीं माँगे। वह ड्राइंग जो बिल्कुल भी लेआउट नहीं रखती, वह छूट है: नाम के मिलाने के लिए कुछ नहीं है, इसलिए कोई भी नाम अस्वीकार नहीं किया जाता।

### Definition:
```python
@property
def layout_names(self):
    ...
@layout_names.setter
def layout_names(self, value):
    ...
```

### साथ ही देखें
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
