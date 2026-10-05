---
title: "on_conversion_failed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Registriert einen Callback, der aufgerufen wird, wenn eine Dokumentkonvertierung fehlschlägt."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/on_conversion_failed/
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
| on_failed | `Action[ConvertedContext, Exception]` | Callable, die den Fehler behandelt, den Konversionskontext empfängt und die Ausnahme, die den Fehler verursacht hat. |

**Returns:** IConversionHandlerSetup: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### Siehe auch
* class [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/)
