---
title: "on_conversion_failed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Registriert einen Callback, der aufgerufen wird, wenn eine Dokumentkonvertierung fehlschlägt."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registriert einen Rückruf, der aufgerufen wird, wenn eine Dokumentkonvertierung fehlschlägt. Ein erneutes Aufrufen ersetzt jeden zuvor gesetzten Handler.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – eine Aktion zur Behandlung des Fehlers, die den Konversionskontext und die Ausnahme, die den Fehler verursacht hat, erhält. |

**Returns:** IConversionHandlerCompleted – the current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Siehe auch
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
