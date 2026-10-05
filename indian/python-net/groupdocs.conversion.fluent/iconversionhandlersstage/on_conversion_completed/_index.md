---
title: "on_conversion_completed मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक कॉलबैक पंजीकृत करता है जिसे दस्तावेज़ परिवर्तन सफलतापूर्वक पूर्ण होने पर बुलाया जाएगा, पुनः‑आह्वान पर पहले सेट किए गए हैंडलर को बदलते हुए।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

एक कॉलबैक पंजीकृत करता है जिसे दस्तावेज़ परिवर्तन सफलतापूर्वक पूर्ण होने पर बुलाया जाएगा, पुनः‑आह्वान पर पहले सेट किए गए हैंडलर को बदलते हुए।

```python
def on_conversion_completed(self, on_completed):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | पूरा होने को संभालने के लिए एक कार्रवाई, रूपांतरण संदर्भ प्राप्त करती है। |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained. Returns `IConversionHandlersStage`.

### साथ ही देखें
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
