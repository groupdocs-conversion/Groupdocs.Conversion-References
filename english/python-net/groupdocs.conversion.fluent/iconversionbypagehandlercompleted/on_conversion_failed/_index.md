---
title: on_conversion_failed method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Registers a callback to be invoked when a page conversion fails."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registers a callback to be invoked when a page conversion fails. Re-invoking replaces any previously set handler.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Callable that handles the failure, receiving the converted page context and the exception that caused the failure. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### See Also
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
