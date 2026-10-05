---
title: "on_conversion_completed मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "जब दस्तावेज़ रूपांतरण सफलतापूर्वक पूर्ण हो जाए तो कॉलबैक को पंजीकृत करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

एक कॉलबैक पंजीकृत करता है जिसे दस्तावेज़ परिवर्तन सफलतापूर्वक पूर्ण होने पर बुलाया जाएगा। पुनः‑आह्वान करने पर पहले सेट किए गए हैंडलर को बदल देता है।

```python
def on_conversion_completed(self, on_completed):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | कॉल करने योग्य जो पूर्णता को संभालता है, रूपांतरण संदर्भ प्राप्त करता है। |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### साथ ही देखें
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
