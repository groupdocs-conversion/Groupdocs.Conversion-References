---
title: with_events method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Register conversion lifecycle event handlers on a ConversionEvents bag that lives for the converter's lifetime and fires on every conversion run."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Register conversion lifecycle event handlers on a [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) bag that lives for the converter's lifetime and fires on every conversion run.

May be called before or after [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/).  
Multiple calls accumulate: the same internal bag is passed to each `configure` action, so handlers set in earlier calls survive unless overwritten by a later one.

```python
def with_events(self, configure):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Action that mutates the events bag. |

**Returns:** This stage so that further entry-stage calls or `Load` may be chained.

### See Also
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
