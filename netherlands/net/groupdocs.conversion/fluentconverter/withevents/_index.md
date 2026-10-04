---
title: "WithEvents"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Entrystage-variant van de fluent chain die begint met conversie‑levenscyclus‑eventhandlers. Zit op dezelfde entry‑stage als WithSettingsgroupdocs.conversion/fluentconverter/withsettings en de resulterende ConversionEventsgroupdocs.conversion/conversionevents‑bag wordt geactiveerd bij elke conversierun door de converter."
type: docs
weight: 20
url: /nl/net/groupdocs.conversion/fluentconverter/withevents/
---
## FluentConverter.WithEvents method

Entry‑stage-variant van de fluent chain die begint met conversie‑levenscyclus‑eventhandlers. Zit op dezelfde entry‑stage als [`WithSettings`](../withsettings), en de resulterende [`ConversionEvents`](../../conversionevents)-bag wordt geactiveerd bij elke conversierun door de converter.

```csharp
public static IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| configure | Action`1 | Actie die de event‑zak wijzigt. |

### Retourwaarde

De bronselectiefase zodat `Load` kan worden gekoppeld.

### Zie ook

* interface [IConversionFrom](../../../groupdocs.conversion.fluent/iconversionfrom)
* class [ConversionEvents](../../conversionevents)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
