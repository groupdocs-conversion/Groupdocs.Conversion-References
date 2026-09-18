---
title: on_conversion_by_page_failed property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The event handler invoked when conversion by page fails."
type: docs
url: /python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/
is_root: false
weight: 2060
---


## on_conversion_by_page_failed property

The event handler invoked when conversion by page fails.

Honored for back‑compat: the value is merged into the internal events bag at [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) construction (mapping to [`ConversionEvents.on_page_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/)) and is overridden if the same handler is also set on the `events` constructor parameter.

### Definition:
```python
@property
def on_conversion_by_page_failed(self):
    ...
@on_conversion_by_page_failed.setter
def on_conversion_by_page_failed(self, value):
    ...
```

### See Also
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
