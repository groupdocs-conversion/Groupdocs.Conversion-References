---
title: on_conversion_failed method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Registers a callback to be invoked when a page conversion fails."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registers a callback to be invoked when a page conversion fails.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – an action to handle the failure, receiving the converted page context and the exception that caused the failure. |

**Returns:** IConversionByPageHandlerSetup: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### See Also
* class [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/)
