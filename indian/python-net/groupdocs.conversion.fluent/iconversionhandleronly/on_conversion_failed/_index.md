---
title: "on_conversion_failed मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "जब दस्तावेज़ रूपांतरण विफल हो जाए तो कॉलबैक को पंजीकृत करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionhandleronly/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

जब दस्तावेज़ रूपांतरण विफल हो जाए तो कॉलबैक को पंजीकृत करता है।

```python
def on_conversion_failed(self, on_failed):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[`ConversionContext`, `Exception`], Any] – विफलता को संभालने के लिए कार्रवाई, जो रूपांतरण संदर्भ और विफलता का कारण बनने वाले अपवाद को प्राप्त करती है। |

**Returns:** `IConversionHandlerOnly`: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### साथ ही देखें
* class [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/)
