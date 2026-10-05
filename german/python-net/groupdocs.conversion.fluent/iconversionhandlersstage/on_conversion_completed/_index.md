---
title: "on_conversion_completed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Registriert einen Rückruf, der aufgerufen wird, wenn eine Dokumentkonvertierung erfolgreich abgeschlossen ist, und ersetzt bei erneuter Aufrufung jeden zuvor gesetzten Handler."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registriert einen Rückruf, der aufgerufen wird, wenn eine Dokumentkonvertierung erfolgreich abgeschlossen ist, und ersetzt bei erneuter Aufrufung jeden zuvor gesetzten Handler.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Eine Aktion zur Behandlung des Abschlusses, die den Konvertierungskontext erhält. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained. Returns `IConversionHandlersStage`.

### Siehe auch
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
