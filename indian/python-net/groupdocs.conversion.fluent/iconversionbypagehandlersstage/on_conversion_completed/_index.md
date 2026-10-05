---
title: "on_conversion_completed मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक कॉलबैक पंजीकृत करता है जिसे पृष्ठ रूपांतरण सफलतापूर्वक पूर्ण होने पर बुलाया जाएगा, पुनःआह्वान पर पहले सेट किए गए हैंडलर को बदलते हुए।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

एक कॉलबैक पंजीकृत करता है जिसे पृष्ठ रूपांतरण सफलतापूर्वक पूर्ण होने पर बुलाया जाएगा, पुनःआह्वान पर पहले सेट किए गए हैंडलर को बदलते हुए।

```python
def on_conversion_completed(self, on_completed):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | एक कार्रवाई जो पूर्णता को संभालती है, परिवर्तित पृष्ठ संदर्भ प्राप्त करती है। |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### साथ ही देखें
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
