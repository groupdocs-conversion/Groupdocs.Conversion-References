---
title: "propiedad on_conversion_by_page_failed"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "El controlador de eventos invocado cuando la conversión por página falla."
type: docs
url: /es/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/
is_root: false
weight: 2060
---


## on_conversion_by_page_failed property

El controlador de eventos invocado cuando la conversión por página falla.

Respetado por compatibilidad hacia atrás: el valor se fusiona en la bolsa interna de eventos en la construcción de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) (mapeando a [`ConversionEvents.on_page_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/)) y se sobrescribe si el mismo manejador también se establece en el parámetro del constructor `events`.

### Definition:
```python
@property
def on_conversion_by_page_failed(self):
    ...
@on_conversion_by_page_failed.setter
def on_conversion_by_page_failed(self, value):
    ...
```

### Ver también
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
