---
title: "on_conversion_completed methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Registreert een callback die wordt aangeroepen wanneer een documentconversie succesvol wordt voltooid."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registreert een callback die wordt aangeroepen wanneer een documentconversie succesvol wordt voltooid.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Een actie om de voltooiing af te handelen, waarbij de conversie‑context wordt ontvangen. |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### Zie ook
* class [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/)
