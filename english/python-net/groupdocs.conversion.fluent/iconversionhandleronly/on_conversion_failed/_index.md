---
title: on_conversion_failed method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Registers a callback to be invoked when a document conversion fails."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionhandleronly/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registers a callback to be invoked when a document conversion fails.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[`ConversionContext`, `Exception`], Any] – Action to handle the failure, receiving the conversion context and the exception that caused the failure. |

**Returns:** `IConversionHandlerOnly`: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### See Also
* class [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/)
