---
title: "on_conversion_failed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Registriert einen Callback, der aufgerufen wird, wenn eine Dokumentkonvertierung fehlschlägt."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionhandleronly/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registriert einen Callback, der aufgerufen wird, wenn eine Dokumentkonvertierung fehlschlägt.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[`ConversionContext`, `Exception`], Any] – Aktion zum Behandeln des Fehlers, wobei der Konvertierungskontext und die Ausnahme, die den Fehler verursacht hat, übergeben werden. |

**Returns:** `IConversionHandlerOnly`: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### Siehe auch
* class [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/)
