---
title: on_conversion_completed method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Receive converted page stream."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Receive converted page stream. Will be fired only if `ConvertTo(convertedStreamProvider)` is set.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Converted page stream provider converted_page_stream arg1arg1: The `ConvertedPageContext` |

**Returns:** Interface to continue conversion building

### See Also
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
