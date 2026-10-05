---
title: "on_conversion_completed मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "परिवर्तित पृष्ठ स्ट्रीम प्राप्त करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_page_stream}

परिवर्तित पृष्ठ स्ट्रीम प्राप्त करता है। केवल तभी सक्रिय होगा जब `ConvertTo(convertedStreamProvider)` सेट किया गया हो।

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | परिवर्तित पृष्ठ स्ट्रीम प्रदाता। `ConvertedPageContext`। |

**Returns:** Interface to continue conversion building.

### साथ ही देखें
* class [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/)
