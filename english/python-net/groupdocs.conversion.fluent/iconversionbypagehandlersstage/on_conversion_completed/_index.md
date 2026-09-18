---
title: on_conversion_completed method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Registers a callback to be invoked when a page conversion completes successfully, replacing any previously set handler on re-invocation."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registers a callback to be invoked when a page conversion completes successfully, replacing any previously set handler on re-invocation.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | An action to handle the completion, receiving the converted page context. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### See Also
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
