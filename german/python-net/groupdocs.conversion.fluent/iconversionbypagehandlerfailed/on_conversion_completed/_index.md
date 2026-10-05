---
title: "on_conversion_completed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Registriert einen Callback, der aufgerufen wird, wenn eine Seitenkonvertierung erfolgreich abgeschlossen wird."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registriert einen Callback, der aufgerufen wird, wenn eine Seitenkonvertierung erfolgreich abgeschlossen wird.

Ein erneutes Aufrufen ersetzt jeden zuvor gesetzten Handler.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | Eine Aktion zur Behandlung des Abschlusses, die den Kontext der konvertierten Seite erhält. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Siehe auch
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
