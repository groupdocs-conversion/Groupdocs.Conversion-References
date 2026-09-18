---
title: listener property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The converter listener implementation used for monitoring conversion status and progress, with its Started, Progress, and Completed callbacks forwarded to ConversionEvents.onconversionstarted…"
type: docs
url: /python-net/groupdocs.conversion/convertersettings/listener/
is_root: false
weight: 2030
---


## listener property

The converter listener implementation used for monitoring conversion status and progress, with its Started, Progress, and Completed callbacks forwarded to [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), and [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) during [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) construction.

### Definition:
```python
@property
def listener(self):
    ...
@listener.setter
def listener(self, value):
    ...
```

### See Also
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
