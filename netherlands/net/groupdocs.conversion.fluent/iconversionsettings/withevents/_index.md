---
title: "WithEvents"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Registreer conversielevenscyclus‑eventhandlers op een ConversionEventsgroupdocs.conversion/conversionevents‑zak die leeft gedurende de levensduur van de converter en wordt geactiveerd bij elke conversierun. Zit op dezelfde instapfase als WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings. Meerdere oproepen stapelen zich op; dezelfde interne bag wordt doorgegeven aan elke configure‑actie, zodat handlers die in eerdere oproepen zijn ingesteld behouden blijven, tenzij ze door een latere oproep worden overschreven."
type: docs
weight: 10
url: /nl/net/groupdocs.conversion.fluent/iconversionsettings/withevents/
---
## IConversionSettings.WithEvents method

Registreer conversielevenscyclus‑eventhandlers op een [`ConversionEvents`](../../../groupdocs.conversion/conversionevents)‑zak die gedurende de levensduur van de converter bestaat en bij elke conversierun wordt geactiveerd. Zit op dezelfde instapfase als [`WithSettings`](../withsettings). Meerdere oproepen stapelen zich op: dezelfde interne zak wordt doorgegeven aan elke *configure*‑actie, zodat handlers die in eerdere oproepen zijn ingesteld behouden blijven, tenzij ze door een latere oproep worden overschreven.

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| configure | Action`1 | Actie die de event‑zak wijzigt. |

### Retourwaarde

De bronselectiefase zodat `Load` kan worden gekoppeld.

### Zie ook

* interface [IConversionFrom](../../iconversionfrom)
* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionSettings](../../iconversionsettings)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
