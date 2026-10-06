---
title: "propiedad listener"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "La implementación del listener del convertidor utilizada para monitorizar el estado y progreso de la conversión, con sus callbacks Started, Progress y Completed reenviados a ConversionEvents.onconversionstarted…"
type: docs
url: /es/python-net/groupdocs.conversion/convertersettings/listener/
is_root: false
weight: 2030
---


## listener property

La implementación del listener del convertidor utilizada para monitorear el estado y progreso de la conversión, con sus callbacks Started, Progress y Completed reenviados a [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), y [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) durante la construcción de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

### Definition:
```python
@property
def listener(self):
    ...
@listener.setter
def listener(self, value):
    ...
```

### Ver también
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
