---
title: "on_conversion_failed methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Registreert een callback die wordt aangeroepen wanneer een documentconversie mislukt."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registreert een callback die wordt aangeroepen wanneer een documentconversie mislukt.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Een actie om de fout af te handelen, die de conversie‑context en de uitzondering die de fout veroorzaakte ontvangt. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Zie ook
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
