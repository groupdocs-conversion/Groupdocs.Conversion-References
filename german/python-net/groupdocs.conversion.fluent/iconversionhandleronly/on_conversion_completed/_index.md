---
title: "on_conversion_completed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Registriert einen Callback, der aufgerufen wird, wenn eine Dokumentkonvertierung erfolgreich abgeschlossen wird."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionhandleronly/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registriert einen Callback, der aufgerufen wird, wenn eine Dokumentkonvertierung erfolgreich abgeschlossen wird.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Eine Aktion zur Behandlung des Abschlusses, die den Konvertierungskontext erhält. |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### Siehe auch
* class [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/)
