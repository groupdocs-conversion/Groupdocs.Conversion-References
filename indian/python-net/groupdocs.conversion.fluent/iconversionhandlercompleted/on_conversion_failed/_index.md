---
title: "on_conversion_failed मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "जब दस्तावेज़ रूपांतरण विफल हो जाए तो कॉलबैक को पंजीकृत करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

जब दस्तावेज़ परिवर्तन विफल हो तो बुलाए जाने वाले कॉलबैक को पंजीकृत करता है। पुनः‑बुलाने से पहले सेट किए गए हैंडलर को बदल दिया जाता है।

```python
def on_conversion_failed(self, on_failed):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – विफलता को संभालने के लिए एक क्रिया, जो रूपांतरण संदर्भ और विफलता का कारण बनी अपवाद को प्राप्त करती है। |

**Returns:** IConversionHandlerCompleted – the current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### साथ ही देखें
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
