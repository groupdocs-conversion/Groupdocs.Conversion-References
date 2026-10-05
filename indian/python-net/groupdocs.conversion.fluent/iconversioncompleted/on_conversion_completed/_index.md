---
title: "on_conversion_completed मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "परिवर्तित दस्तावेज़ स्ट्रीम प्राप्त करता है और केवल तभी सक्रिय होता है जब ConvertTo(string fileName) या ConvertTo(convertedStreamProvider) सेट किया गया हो।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversioncompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_file_stream}

परिवर्तित दस्तावेज़ स्ट्रीम प्राप्त करता है और केवल तब ही ट्रिगर होता है जब `ConvertTo(string fileName)` या `ConvertTo(convertedStreamProvider)` सेट किया गया हो।

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | परिवर्तित दस्तावेज़ स्ट्रीम प्रदाता। |

**Returns:** Interface to continue conversion building.

### साथ ही देखें
* class [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/)
