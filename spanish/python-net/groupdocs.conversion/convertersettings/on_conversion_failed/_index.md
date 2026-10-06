---
title: "propiedad on_conversion_failed"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "El controlador de eventos invocado cuando una conversión falla."
type: docs
url: /es/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/
is_root: false
weight: 2070
---


## on_conversion_failed property

El controlador de eventos invocado cuando una conversión falla.

Conservado por compatibilidad retroactiva: el valor se fusiona en la bolsa interna de eventos al crear [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) (mapeando a [`ConversionEvents.on_document_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/)) y se sobrescribe si el mismo controlador también se establece en el parámetro del constructor `events`.

### Definition:
```python
@property
def on_conversion_failed(self):
    ...
@on_conversion_failed.setter
def on_conversion_failed(self, value):
    ...
```

### Ver también
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
