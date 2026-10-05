---
title: "on_conversion_completed मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "परिवर्तित दस्तावेज़ स्ट्रीम को प्राप्त करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

परिवर्तित दस्तावेज़ स्ट्रीम प्राप्त करता है। यह केवल तब बुलाया जाता है जब `ConvertTo(string fileName)` या `ConvertTo(convertedStreamProvider)` कॉन्फ़िगर किया गया हो।

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | परिवर्तित दस्तावेज़ स्ट्रीम के लिए प्रदाता। प्रदाता एक `ConvertedContext` प्राप्त करता है। |

**Returns:** Interface to continue conversion building.

### साथ ही देखें
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
