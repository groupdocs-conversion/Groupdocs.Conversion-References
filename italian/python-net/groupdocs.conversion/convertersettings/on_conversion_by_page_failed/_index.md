---
title: "proprietà on_conversion_by_page_failed"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Il gestore dell'evento invocato quando la conversione per pagina fallisce."
type: docs
url: /it/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/
is_root: false
weight: 2060
---


## on_conversion_by_page_failed property

Il gestore dell'evento invocato quando la conversione per pagina fallisce.

Rispettato per compatibilità retroattiva: il valore viene unito al contenitore interno di eventi durante la costruzione di [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) (mappando a [`ConversionEvents.on_page_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/)) e viene sovrascritto se lo stesso gestore è impostato anche sul parametro costruttore `events`.

### Definition:
```python
@property
def on_conversion_by_page_failed(self):
    ...
@on_conversion_by_page_failed.setter
def on_conversion_by_page_failed(self, value):
    ...
```

### Vedi anche
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
