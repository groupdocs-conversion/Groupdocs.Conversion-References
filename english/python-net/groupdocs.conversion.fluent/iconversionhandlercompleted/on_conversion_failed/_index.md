---
title: on_conversion_failed method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Registers a callback to be invoked when a document conversion fails."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registers a callback to be invoked when a document conversion fails. Re‑invoking replaces any previously set handler.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – an action to handle the failure, receiving the conversion context and the exception that caused the failure. |

**Returns:** IConversionHandlerCompleted – the current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### See Also
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
