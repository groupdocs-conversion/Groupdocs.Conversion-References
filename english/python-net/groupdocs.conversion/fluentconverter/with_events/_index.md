---
title: with_events method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Starts a fluent chain at the entry stage with conversion lifecycle event handlers."
type: docs
url: /python-net/groupdocs.conversion/fluentconverter/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Starts a fluent chain at the entry stage with conversion lifecycle event handlers.

```python
def with_events(cls, configure):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Callable that mutates the `ConversionEvents` bag. |

**Returns:** The source-selection stage, allowing `Load` to be chained.

### See Also
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
