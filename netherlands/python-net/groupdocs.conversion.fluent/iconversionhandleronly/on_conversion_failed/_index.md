---
title: "on_conversion_failed methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Registreert een callback die wordt aangeroepen wanneer een documentconversie mislukt."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionhandleronly/on_conversion_failed/
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
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[`ConversionContext`, `Exception`], Any] – Actie om de fout af te handelen, waarbij de conversiecontext en de uitzondering die de fout veroorzaakte worden ontvangen. |

**Returns:** `IConversionHandlerOnly`: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### Zie ook
* class [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/)
