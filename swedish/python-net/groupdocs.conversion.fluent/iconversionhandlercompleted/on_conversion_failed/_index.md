---
title: "on_conversion_failed metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Registrerar en återuppringning som ska anropas när en dokumentkonvertering misslyckas."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registrerar en återuppringning som ska anropas när en dokumentkonvertering misslyckas. Om‑anrop ersätter eventuellt tidigare angiven hanterare.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – en åtgärd för att hantera felet, som tar emot konverteringskontexten och undantaget som orsakade felet. |

**Returns:** IConversionHandlerCompleted – the current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Se även
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
