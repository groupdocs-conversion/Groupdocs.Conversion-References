---
title: "on_conversion_failed methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Registreert een callback die wordt aangeroepen wanneer een paginaconversie mislukt."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registreert een callback die wordt aangeroepen wanneer een paginaconversie mislukt.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – een actie om de fout af te handelen, waarbij de geconverteerde paginacontext en de uitzondering die de fout veroorzaakte worden ontvangen. |

**Returns:** IConversionByPageHandlerSetup: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### Zie ook
* class [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/)
