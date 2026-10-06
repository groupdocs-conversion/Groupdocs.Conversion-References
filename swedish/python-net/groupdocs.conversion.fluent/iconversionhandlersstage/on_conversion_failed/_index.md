---
title: "on_conversion_failed metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Registrerar en återuppringning som ska anropas när en dokumentkonvertering misslyckas."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registrerar en återuppringning som ska anropas när en dokumentkonvertering misslyckas.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | En åtgärd för att hantera felet, som tar emot konverteringskontexten och undantaget som orsakade felet. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Se även
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
