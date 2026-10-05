---
title: "Eigenschaft listener"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die Implementierung des Converter‑Listeners, die zur Überwachung des Konvertierungsstatus und -fortschritts verwendet wird, wobei ihre Started-, Progress- und Completed‑Callbacks an ConversionEvents.onconversionstarted weitergeleitet werden…"
type: docs
url: /de/python-net/groupdocs.conversion/convertersettings/listener/
is_root: false
weight: 2030
---


## listener property

Die Implementierung des Converter-Listeners, die zur Überwachung des Konvertierungsstatus und -fortschritts verwendet wird, wobei ihre Started-, Progress- und Completed-Callbacks an [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), und [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) während der Konstruktion von [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) weitergeleitet werden.

### Definition:
```python
@property
def listener(self):
    ...
@listener.setter
def listener(self, value):
    ...
```

### Siehe auch
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
