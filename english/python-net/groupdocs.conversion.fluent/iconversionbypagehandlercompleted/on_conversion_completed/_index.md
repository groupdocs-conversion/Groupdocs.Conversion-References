---
title: on_conversion_completed method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Registers a callback to be invoked when a page conversion completes successfully."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registers a callback to be invoked when a page conversion completes successfully.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | An action to handle the completion, receiving the converted page context. |

**Returns:** The flat by-page handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### See Also
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
