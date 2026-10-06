---
title: "on_conversion_failed methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Registreert een callback die wordt aangeroepen wanneer een paginaconversie mislukt."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registreert een callback die wordt aangeroepen wanneer een paginaconversie mislukt. Opnieuw aanroepen vervangt elke eerder ingestelde handler.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Aanroepbaar object dat de fout afhandelt, waarbij de geconverteerde paginacontext en de uitzondering die de fout veroorzaakte worden ontvangen. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Zie ook
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
