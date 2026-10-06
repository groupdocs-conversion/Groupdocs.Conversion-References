---
title: "on_conversion_failed methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Registreert een callback die wordt aangeroepen wanneer een paginaconversie mislukt, waarbij elke eerder ingestelde handler bij her‑aanroep wordt vervangen."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Registreert een callback die wordt aangeroepen wanneer een paginaconversie mislukt, waarbij elke eerder ingestelde handler bij her‑aanroep wordt vervangen.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Aanroepbaar object dat de fout afhandelt, waarbij de geconverteerde paginacontext en de uitzondering die de fout veroorzaakte worden ontvangen. |

**Returns:** IConversionByPageHandlersStage: This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Zie ook
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
