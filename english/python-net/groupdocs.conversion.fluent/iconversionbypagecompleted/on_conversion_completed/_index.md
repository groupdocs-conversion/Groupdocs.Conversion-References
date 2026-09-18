---
title: on_conversion_completed method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Receives the converted page stream."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_page_stream}

Receives the converted page stream. Will be fired only if `ConvertTo(convertedStreamProvider)` is set.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Converted page stream provider. The `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### See Also
* class [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/)
