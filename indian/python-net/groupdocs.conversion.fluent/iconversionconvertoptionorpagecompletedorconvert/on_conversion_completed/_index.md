---
title: "on_conversion_completed मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "कन्वर्टेड पेज स्ट्रीम प्राप्त करें।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

परिवर्तित पृष्ठ स्ट्रीम प्राप्त करें। यह केवल तब सक्रिय होगा जब `ConvertTo(convertedStreamProvider)` सेट किया गया हो।

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | कन्वर्टेड पेज स्ट्रीम प्रोवाइडर converted_page_stream arg1arg1: `ConvertedPageContext` |

**Returns:** Interface to continue conversion building

### साथ ही देखें
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
