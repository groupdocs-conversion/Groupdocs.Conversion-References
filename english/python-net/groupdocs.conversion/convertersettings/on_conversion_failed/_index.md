---
title: on_conversion_failed property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The event handler invoked when a conversion fails."
type: docs
url: /python-net/groupdocs.conversion/convertersettings/on_conversion_failed/
is_root: false
weight: 2070
---


## on_conversion_failed property

The event handler invoked when a conversion fails.

Honored for back‑compat: the value is merged into the internal events bag at [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) construction (mapping to [`ConversionEvents.on_document_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/)) and is overridden if the same handler is also set on the `events` constructor parameter.

### Definition:
```python
@property
def on_conversion_failed(self):
    ...
@on_conversion_failed.setter
def on_conversion_failed(self, value):
    ...
```

### See Also
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
