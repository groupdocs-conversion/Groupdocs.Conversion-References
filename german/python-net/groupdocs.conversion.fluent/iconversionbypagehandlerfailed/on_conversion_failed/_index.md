---
title: "on_conversion_failed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Registriert einen Callback, der aufgerufen wird, wenn eine Seitenkonvertierung fehlschlägt."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/on_conversion_failed/
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
| on_failed | `Action[ConvertedPageContext, Exception]` | Eine Aktion zur Behandlung des Fehlers, die den Kontext der konvertierten Seite und die Ausnahme, die den Fehler verursacht hat, erhält. |

**Returns:** The flat by-page handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### Siehe auch
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
