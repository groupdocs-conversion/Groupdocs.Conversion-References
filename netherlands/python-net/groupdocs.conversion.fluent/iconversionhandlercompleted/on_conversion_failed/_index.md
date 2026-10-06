---
title: "on_conversion_failed methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Registreert een callback die wordt aangeroepen wanneer een documentconversie mislukt."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registreert een callback die wordt aangeroepen wanneer een documentconversie mislukt. Opnieuw aanroepen vervangt elke eerder ingestelde handler.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – een actie om de fout af te handelen, waarbij de conversiecontext en de uitzondering die de fout veroorzaakte worden ontvangen. |

**Returns:** IConversionHandlerCompleted – the current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Zie ook
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
