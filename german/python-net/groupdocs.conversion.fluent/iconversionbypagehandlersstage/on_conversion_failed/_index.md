---
title: "on_conversion_failed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Registriert einen Rückruf, der aufgerufen wird, wenn eine Seitenkonvertierung fehlschlägt, und ersetzt dabei jeden zuvor gesetzten Handler bei erneutem Aufruf."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registriert einen Rückruf, der aufgerufen wird, wenn eine Seitenkonvertierung fehlschlägt, und ersetzt dabei jeden zuvor gesetzten Handler bei erneutem Aufruf.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Aufrufbare, die den Fehler behandelt, den konvertierten Seitenkontext empfängt und die Ausnahme, die den Fehler verursacht hat. |

**Returns:** IConversionByPageHandlersStage: This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Siehe auch
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
