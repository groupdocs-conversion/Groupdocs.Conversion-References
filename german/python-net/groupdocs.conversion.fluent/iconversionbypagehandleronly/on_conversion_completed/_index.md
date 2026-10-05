---
title: "on_conversion_completed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Registriert einen Callback, der aufgerufen wird, wenn eine Seitenkonvertierung erfolgreich abgeschlossen wird."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registriert einen Callback, der aufgerufen wird, wenn eine Seitenkonvertierung erfolgreich abgeschlossen wird.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | Callable, die den Abschluss behandelt und den konvertierten Seitenkontext erhält. |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### Siehe auch
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
