---
title: "on_conversion_completed मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "जब पृष्ठ रूपांतरण सफलतापूर्वक पूर्ण हो जाए तो कॉलबैक को पंजीकृत करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

जब पृष्ठ रूपांतरण सफलतापूर्वक पूर्ण हो जाए तो कॉलबैक को पंजीकृत करता है।

```python
def on_conversion_completed(self, on_completed):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | एक कार्रवाई जो पूर्णता को संभालती है, परिवर्तित पृष्ठ संदर्भ प्राप्त करती है। |

**Returns:** The flat by-page handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### साथ ही देखें
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
