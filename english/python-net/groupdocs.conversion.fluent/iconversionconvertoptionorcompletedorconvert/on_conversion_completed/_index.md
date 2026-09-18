---
title: on_conversion_completed method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Receives the converted document stream."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

Receives the converted document stream. It is invoked only when `ConvertTo(string fileName)` or `ConvertTo(convertedStreamProvider)` has been configured.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Provider for the converted document stream. The provider receives a `ConvertedContext`. |

**Returns:** Interface to continue conversion building.

### See Also
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
