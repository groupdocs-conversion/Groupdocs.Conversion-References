---
title: "Eigenschaft on_conversion_failed"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Der Ereignishandler, der aufgerufen wird, wenn eine Konvertierung fehlschlägt."
type: docs
url: /de/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/
is_root: false
weight: 2070
---


## on_conversion_failed property

Der Ereignishandler, der aufgerufen wird, wenn eine Konvertierung fehlschlägt.

Für die Rückwärtskompatibilität berücksichtigt: Der Wert wird beim Erstellen des internen Ereignisbehälters bei [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) zusammengeführt (zugeordnet zu [`ConversionEvents.on_document_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/)) und überschrieben, wenn derselbe Handler ebenfalls im Konstruktorparameter `events` gesetzt ist.

### Definition:
```python
@property
def on_conversion_failed(self):
    ...
@on_conversion_failed.setter
def on_conversion_failed(self, value):
    ...
```

### Siehe auch
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
