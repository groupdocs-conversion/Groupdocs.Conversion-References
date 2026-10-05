---
title: "on_conversion_failed मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "जब दस्तावेज़ रूपांतरण विफल हो जाए तो कॉलबैक को पंजीकृत करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/on_conversion_failed/
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
| on_failed | `Action[ConvertedContext, Exception]` | कॉलएबल जो विफलता को संभालता है, रूपांतरण संदर्भ और वह अपवाद प्राप्त करता है जिसने विफलता उत्पन्न की। |

**Returns:** The flat handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### साथ ही देखें
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
