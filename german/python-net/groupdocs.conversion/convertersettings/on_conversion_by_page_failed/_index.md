---
title: "Eigenschaft on_conversion_by_page_failed"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Der Ereignishandler, der aufgerufen wird, wenn die Konvertierung pro Seite fehlschlägt."
type: docs
url: /de/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/
is_root: false
weight: 2060
---


## on_conversion_by_page_failed property

Der Ereignishandler, der aufgerufen wird, wenn die Konvertierung pro Seite fehlschlägt.

Für die Rückwärtskompatibilität berücksichtigt: Der Wert wird beim Erstellen des internen Ereignisbehälters bei [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) zusammengeführt (zugeordnet zu [`ConversionEvents.on_page_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/)) und überschrieben, wenn derselbe Handler ebenfalls im Konstruktorparameter `events` gesetzt ist.

### Definition:
```python
@property
def on_conversion_by_page_failed(self):
    ...
@on_conversion_by_page_failed.setter
def on_conversion_by_page_failed(self, value):
    ...
```

### Siehe auch
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
