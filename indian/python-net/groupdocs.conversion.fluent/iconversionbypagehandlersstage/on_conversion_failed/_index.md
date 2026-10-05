---
title: "on_conversion_failed मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक कॉलबैक पंजीकृत करता है जिसे पृष्ठ रूपांतरण विफल होने पर बुलाया जाएगा, पुनःआह्वान पर पहले सेट किए गए हैंडलर को बदलते हुए।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

एक कॉलबैक पंजीकृत करता है जिसे पृष्ठ रूपांतरण विफल होने पर बुलाया जाएगा, पुनःआह्वान पर पहले सेट किए गए हैंडलर को बदलते हुए।

```python
def on_conversion_failed(self, on_failed):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | एक कॉलेबल जो विफलता को संभालता है, परिवर्तित पृष्ठ संदर्भ और वह अपवाद प्राप्त करता है जिसने विफलता का कारण बना। |

**Returns:** IConversionByPageHandlersStage: This stage, so additional handlers or `Convert` / `Compress` may be chained.

### साथ ही देखें
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
