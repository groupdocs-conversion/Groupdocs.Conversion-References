---
title: "IConversionSettings"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Stel conversie‑instellingen of -gebeurtenissen in op het instapstadium vóór Load."
type: docs
weight: 1540
url: /nl/net/groupdocs.conversion.fluent/iconversionsettings/
---
## IConversionSettings interface

Instellen van conversie‑instellingen of gebeurtenissen in de instapfase (voor `Load`).

```csharp
public interface IConversionSettings
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionsettings/withevents)(Action&lt;ConversionEvents&gt;) | Registreer conversielevenscyclus‑gebeurtenishandlers op een [`ConversionEvents`](../../groupdocs.conversion/conversionevents) container die gedurende de levensduur van de converter bestaat en bij elke conversierun wordt geactiveerd. Zit op hetzelfde instapstadium als [`WithSettings`](./withsettings). Meerdere oproepen worden opgeteld: dezelfde interne container wordt doorgegeven aan elke *configure*-actie, zodat handlers die in eerdere oproepen zijn ingesteld behouden blijven, tenzij ze door een latere worden overschreven. |
| [WithSettings](../../groupdocs.conversion.fluent/iconversionsettings/withsettings)(Func&lt;ConverterSettings&gt;) | Stel converterinstellingen in |

### Zie ook

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
