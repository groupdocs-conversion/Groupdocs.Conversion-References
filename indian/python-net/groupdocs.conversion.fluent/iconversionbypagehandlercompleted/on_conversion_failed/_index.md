---
title: "on_conversion_failed मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "जब पृष्ठ रूपांतरण विफल हो जाए तो कॉलबैक को पंजीकृत करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

पृष्ठ रूपांतरण विफल होने पर कॉलबैक को पंजीकृत करता है। पुनः-आह्वान करने से पहले सेट किए गए किसी भी हैंडलर को बदल दिया जाता है।

```python
def on_conversion_failed(self, on_failed):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | एक कॉलेबल जो विफलता को संभालता है, परिवर्तित पृष्ठ संदर्भ और वह अपवाद प्राप्त करता है जिसने विफलता का कारण बना। |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### साथ ही देखें
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
