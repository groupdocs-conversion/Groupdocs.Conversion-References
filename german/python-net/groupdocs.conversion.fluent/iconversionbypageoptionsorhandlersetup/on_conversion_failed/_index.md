---
title: "on_conversion_failed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Registriert einen Callback, der aufgerufen wird, wenn eine Seitenkonvertierung fehlschlägt."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registriert einen Callback, der aufgerufen wird, wenn eine Seitenkonvertierung fehlschlägt.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Aufrufbare, die den Fehler behandelt, den konvertierten Seitenkontext empfängt und die Ausnahme, die den Fehler verursacht hat. |

**Returns:** Interface to continue conversion building, allowing only `OnConversionCompleted` or `Convert`/`Compress`.

### Siehe auch
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
