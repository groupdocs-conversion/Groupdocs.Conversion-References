---
title: "on_conversion_completed मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "परिवर्तित पृष्ठ स्ट्रीम प्राप्त करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

परिवर्तित पृष्ठ स्ट्रीम प्राप्त करता है। केवल तब ही ट्रिगर होता है जब `ConvertTo(convertedStreamProvider)` सेट किया गया हो।

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | परिवर्तित पृष्ठ स्ट्रीम प्रदाता। प्रदाता एक `ConvertedPageContext` प्राप्त करता है। |

**Returns:** Interface to continue conversion building.

### साथ ही देखें
* class [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/)
