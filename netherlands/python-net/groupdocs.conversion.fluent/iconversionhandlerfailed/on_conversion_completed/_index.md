---
title: "on_conversion_completed methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Registreert een callback die wordt aangeroepen wanneer een documentconversie succesvol wordt voltooid."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registreert een callback die wordt aangeroepen wanneer een documentconversie succesvol wordt voltooid. Opnieuw aanroepen vervangt elke eerder ingestelde handler.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Callable die de voltooiing afhandelt en de conversie‑context ontvangt. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Zie ook
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
