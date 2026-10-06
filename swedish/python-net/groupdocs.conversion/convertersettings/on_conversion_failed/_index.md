---
title: "on_conversion_failed egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Händelsehanteraren som anropas när en konvertering misslyckas."
type: docs
url: /sv/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/
is_root: false
weight: 2070
---


## on_conversion_failed property

Händelsehanteraren som anropas när en konvertering misslyckas.

Respekteras för bakåtkompatibilitet: värdet slås samman med den interna händelsepåsen vid konstruktion av [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) (mappas till [`ConversionEvents.on_document_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/)) och åsidosätts om samma hanterare också anges på konstruktörsparametern `events`.

### Definition:
```python
@property
def on_conversion_failed(self):
    ...
@on_conversion_failed.setter
def on_conversion_failed(self, value):
    ...
```

### Se även
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
