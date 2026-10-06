---
title: "on_conversion_completed methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Registreert een callback die wordt aangeroepen wanneer een paginaconversie succesvol wordt voltooid, waarbij elke eerder ingestelde handler bij heraanroep wordt vervangen."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Registreert een callback die wordt aangeroepen wanneer een paginaconversie succesvol wordt voltooid, waarbij elke eerder ingestelde handler bij heraanroep wordt vervangen.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | Een actie om de voltooiing af te handelen, waarbij de geconverteerde paginacontext wordt ontvangen. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Zie ook
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
