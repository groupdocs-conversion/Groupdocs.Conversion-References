---
title: on_conversion_completed method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Receives the converted document stream and is fired only if ConvertTo(string fileName) or ConvertTo(convertedStreamProvider) is set."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversioncompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_file_stream}

Receives the converted document stream and is fired only if `ConvertTo(string fileName)` or `ConvertTo(convertedStreamProvider)` is set.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Converted document stream provider. |

**Returns:** Interface to continue conversion building.

### See Also
* class [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/)
