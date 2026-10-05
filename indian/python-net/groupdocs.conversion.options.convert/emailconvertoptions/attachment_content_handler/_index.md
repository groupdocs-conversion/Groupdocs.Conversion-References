---
title: "attachment_content_handler प्रॉपर्टी"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "ईमेल अटैचमेंट्स की कस्टम प्रोसेसिंग को संभालने के लिए उपयोग किया जाने वाला प्रतिनिधि।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.convert/emailconvertoptions/attachment_content_handler/
is_root: false
weight: 2010
---


## attachment_content_handler property

ईमेल अटैचमेंट्स की कस्टम प्रोसेसिंग को संभालने के लिए उपयोग किया जाने वाला प्रतिनिधि।

डेलीगेट अटैचमेंट नाम (`str`), कंटेंट टाइप (`str`), और मूल अटैचमेंट स्ट्रीम (`io.RawIOBase`) प्राप्त करता है, और उसे संशोधित अटैचमेंट स्ट्रीम (`io.RawIOBase`) लौटाना चाहिए।

### Definition:
```python
@property
def attachment_content_handler(self):
    ...
@attachment_content_handler.setter
def attachment_content_handler(self, value):
    ...
```

### साथ ही देखें
* class [`EmailConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/emailconvertoptions/)
