---
title: on_conversion_completed method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Registers a callback to be invoked when a document conversion completes successfully."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registers a callback to be invoked when a document conversion completes successfully. Re‑invoking replaces any previously set handler.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Callable that handles the completion, receiving the conversion context. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### See Also
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
