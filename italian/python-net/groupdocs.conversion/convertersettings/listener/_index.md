---
title: "proprietà listener"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "L'implementazione del listener del converter utilizzata per monitorare lo stato e l'avanzamento della conversione, con i callback Started, Progress e Completed inoltrati a ConversionEvents.onconversionstarted…"
type: docs
url: /it/python-net/groupdocs.conversion/convertersettings/listener/
is_root: false
weight: 2030
---


## listener property

L'implementazione del listener del convertitore usata per monitorare lo stato e l'avanzamento della conversione, con i suoi callback Started, Progress e Completed inoltrati a [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), e [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) durante la costruzione di [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

### Definition:
```python
@property
def listener(self):
    ...
@listener.setter
def listener(self, value):
    ...
```

### Vedi anche
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
