---
title: on_conversion_completed method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Registers a callback to be invoked when a document conversion completes successfully."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionhandleronly/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registers a callback to be invoked when a document conversion completes successfully.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | An action to handle the completion, receiving the conversion context. |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### See Also
* class [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/)
