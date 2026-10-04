---
title: "WithEvents"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Registreer conversielevenscyclus‑eventhandlers op een ConversionEventsgroupdocs.conversion/conversionevents‑zak die leeft gedurende de levensduur van de converter en wordt geactiveerd bij elke conversierun. Kan worden aangeroepen vóór of na WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings. Meerdere oproepen stapelen zich op; dezelfde interne zak wordt doorgegeven aan elke configure‑actie, zodat handlers die in eerdere oproepen zijn ingesteld behouden blijven, tenzij ze door een latere worden overschreven."
type: docs
weight: 20
url: /nl/net/groupdocs.conversion.fluent/iconversionfrom/withevents/
---
## IConversionFrom.WithEvents method

Registreer conversielevenscyclus‑eventhandlers op een [`ConversionEvents`](../../../groupdocs.conversion/conversionevents)‑zak die leeft gedurende de levensduur van de converter en wordt geactiveerd bij elke conversierun. Kan worden aangeroepen vóór of na [`WithSettings`](../../iconversionsettings/withsettings). Meerdere oproepen stapelen zich op: dezelfde interne zak wordt doorgegeven aan elke *configure*‑actie, zodat handlers die in eerdere oproepen zijn ingesteld behouden blijven, tenzij ze door een latere worden overschreven.

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| configure | Action`1 | Actie die de event‑zak wijzigt. |

### Retourwaarde

Deze fase zodat verdere entry‑stage‑oproepen of `Load` kunnen worden gekoppeld.

### Zie ook

* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
