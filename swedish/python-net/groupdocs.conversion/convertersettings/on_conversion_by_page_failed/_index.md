---
title: "egenskapen on_conversion_by_page_failed"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Händelsehanteraren som anropas när konvertering per sida misslyckas."
type: docs
url: /sv/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/
is_root: false
weight: 2060
---


## on_conversion_by_page_failed property

Händelsehanteraren som anropas när konvertering per sida misslyckas.

Respekteras för bakåtkompatibilitet: värdet slås samman med den interna händelsepåsen vid konstruktion av [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) (mappas till [`ConversionEvents.on_page_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/)) och åsidosätts om samma hanterare också anges på konstruktörsparametern `events`.

### Definition:
```python
@property
def on_conversion_by_page_failed(self):
    ...
@on_conversion_by_page_failed.setter
def on_conversion_by_page_failed(self, value):
    ...
```

### Se även
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
