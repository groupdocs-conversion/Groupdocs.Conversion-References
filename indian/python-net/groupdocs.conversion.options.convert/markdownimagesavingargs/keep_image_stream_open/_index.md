---
title: "keep_image_stream_open प्रॉपर्टी"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "यह प्रॉपर्टी निर्धारित करती है कि रूपांतरण के बाद कनवर्टर छवि स्ट्रीम को खुला रखता है या नहीं।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

यह प्रॉपर्टी निर्धारित करती है कि रूपांतरण के बाद कनवर्टर छवि स्ट्रीम को खुला रखता है या नहीं।

जब False (डिफ़ॉल्ट) हो, तो कनवर्टर लिखने के बाद [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/) को बंद कर देता है — यह `io.RawIOBase` रिप्लेसमेंट्स के लिए सामान्य है जिन्हें डिस्क पर फ्लश किया जाना चाहिए। इसे True पर सेट करें ताकि रूपांतरण पूर्ण होने के बाद स्ट्रीम खुला रहे (आमतौर पर `io.BytesIO` जिसे आप स्वयं पढ़ना चाहते हैं); फिर कॉलर को डिस्पोज़ल का अधिकार मिलता है।

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### साथ ही देखें
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
