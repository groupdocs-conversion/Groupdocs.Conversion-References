---
title: "proprietà on_conversion_failed"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Il gestore dell'evento invocato quando una conversione fallisce."
type: docs
url: /it/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/
is_root: false
weight: 2070
---


## on_conversion_failed property

Il gestore dell'evento invocato quando una conversione fallisce.

Onorato per retro‑compatibilità: il valore viene unito al sacchetto interno degli eventi durante la costruzione di [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) (mappando a [`ConversionEvents.on_document_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/)) e viene sovrascritto se lo stesso gestore è anche impostato sul parametro costruttore `events`.

### Definition:
```python
@property
def on_conversion_failed(self):
    ...
@on_conversion_failed.setter
def on_conversion_failed(self, value):
    ...
```

### Vedi anche
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
