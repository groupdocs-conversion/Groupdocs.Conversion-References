---
title: "eigenschap listener"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De converter‑listenerimplementatie die wordt gebruikt voor het bewaken van de conversiestatus en voortgang, waarbij de callbacks Started, Progress en Completed worden doorgestuurd naar ConversionEvents.onconversionstarted…"
type: docs
url: /nl/python-net/groupdocs.conversion/convertersettings/listener/
is_root: false
weight: 2030
---


## listener property

De implementatie van de converter‑listener die wordt gebruikt voor het bewaken van de conversiestatus en voortgang, waarbij de callbacks Started, Progress en Completed worden doorgestuurd naar [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), en [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) tijdens de constructie van [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

### Definition:
```python
@property
def listener(self):
    ...
@listener.setter
def listener(self, value):
    ...
```

### Zie ook
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
