---
title: "egenskapen listener"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Konverteringslyssnare-implementeringen som används för att övervaka konverteringsstatus och -framsteg, med dess Started-, Progress- och Completed‑återuppringningar vidarebefordrade till ConversionEvents.onconversionstarted…"
type: docs
url: /sv/python-net/groupdocs.conversion/convertersettings/listener/
is_root: false
weight: 2030
---


## listener property

Konverterlyssnare-implementeringen som används för att övervaka konverteringsstatus och framsteg, med dess Started-, Progress- och Completed‑återuppringningar vidarebefordrade till [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), och [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) under konstruktionen av [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

### Definition:
```python
@property
def listener(self):
    ...
@listener.setter
def listener(self, value):
    ...
```

### Se även
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
