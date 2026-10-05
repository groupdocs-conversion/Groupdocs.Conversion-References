---
title: "on_conversion_completed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Registriert einen Callback, der aufgerufen wird, wenn eine Dokumentkonvertierung erfolgreich abgeschlossen wird."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registriert einen Rückruf, der aufgerufen wird, wenn eine Dokumentkonvertierung erfolgreich abgeschlossen ist. Ein erneutes Aufrufen ersetzt jeden zuvor gesetzten Handler.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Callable, die den Abschluss behandelt und den Konvertierungskontext erhält. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Siehe auch
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
