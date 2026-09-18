---
title: with_events method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Registers conversion lifecycle event handlers on a ConversionEvents bag that lives for the converter's lifetime and fires on every conversion run."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/
is_root: false
weight: 1010
---


## with_events {#configure}

Registers conversion lifecycle event handlers on a [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) bag that lives for the converter's lifetime and fires on every conversion run.

Sits at the same entry stage as [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/). Multiple calls accumulate: the same internal bag is passed to each `configure` action, so handlers set in earlier calls survive unless overwritten by a later one.

```python
def with_events(self, configure):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Action that mutates the events bag. |

**Returns:** The source-selection stage so that `Load` may be chained.

### See Also
* class [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/)
