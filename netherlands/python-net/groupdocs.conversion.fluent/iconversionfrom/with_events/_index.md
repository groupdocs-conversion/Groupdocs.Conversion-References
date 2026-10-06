---
title: "with_events-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Registreer levenscyclus‑eventhandlers voor conversie op een ConversionEvents‑zak die gedurende de levensduur van de converter bestaat en bij elke conversierun wordt geactiveerd."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Registreer conversielevenscyclus‑eventhandlers op een [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) container die gedurende de levensduur van de converter bestaat en bij elke conversierun wordt geactiveerd.

Kan worden aangeroepen vóór of na [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/).
Meerdere aanroepen worden opgeteld: dezelfde interne zak wordt doorgegeven aan elke `configure`‑actie, zodat handlers die in eerdere aanroepen zijn ingesteld behouden blijven tenzij ze door een latere worden overschreven.

```python
def with_events(self, configure):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Actie die de events bag wijzigt. |

**Returns:** This stage so that further entry-stage calls or `Load` may be chained.

### Zie ook
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
