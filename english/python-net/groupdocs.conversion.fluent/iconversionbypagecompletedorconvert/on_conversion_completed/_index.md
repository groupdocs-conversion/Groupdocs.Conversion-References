---
title: on_conversion_completed method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Receives the converted page stream."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Receives the converted page stream. Fires only if `ConvertTo(convertedStreamProvider)` is set.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Converted page stream provider. The provider receives a `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### See Also
* class [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/)
