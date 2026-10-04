---
title: "IConversionFrom"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Bron instellen voor conversie"
type: docs
weight: 1440
url: /nl/net/groupdocs.conversion.fluent/iconversionfrom/
---
## IConversionFrom interface

Bron instellen voor conversie

```csharp
public interface IConversionFrom
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_1)(Func&lt;Stream&gt;) | Stel brondocumentstroom in |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load)(Func&lt;Stream[]&gt;) | Stel array met stromen van brondocumenten in |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_2)(string) | Stel bestandsnaam van brondocument in |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_3)(string[]) | Stel array met brondocumenten in |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionfrom/withevents)(Action&lt;ConversionEvents&gt;) | Registreer conversielevenscyclus‑eventhandlers op een [`ConversionEvents`](../../groupdocs.conversion/conversionevents) zak die gedurende de levensduur van de converter bestaat en bij elke conversierun wordt geactiveerd. Kan worden aangeroepen vóór of na [`WithSettings`](../iconversionsettings/withsettings). Meerdere oproepen worden opgeteld: dezelfde interne zak wordt doorgegeven aan elke *configure*-actie, zodat handlers die in eerdere oproepen zijn ingesteld behouden blijven, tenzij ze door een latere worden overschreven. |

### Zie ook

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
