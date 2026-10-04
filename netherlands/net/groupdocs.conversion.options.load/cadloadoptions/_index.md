---
title: "CadLoadOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor het laden van CAD‑documenten."
type: docs
weight: 2430
url: /nl/net/groupdocs.conversion.options.load/cadloadoptions/
---
## CadLoadOptions class

Opties voor het laden van CAD‑documenten.

```csharp
public sealed class CadLoadOptions : LoadOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [CadLoadOptions](cadloadoptions)() | Initialiseert een nieuwe instantie van de klasse [`CadLoadOptions`](../cadloadoptions). |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/cadloadoptions/backgroundcolor) { get; set; } | Haalt of stelt een achtergrondkleur in. |
| [CtbSources](../../groupdocs.conversion.options.load/cadloadoptions/ctbsources) { get; set; } | Haalt of stelt de CTB-bronnen in. |
| [DrawColor](../../groupdocs.conversion.options.load/cadloadoptions/drawcolor) { get; set; } | Haalt of stelt de voorgrondkleur in. |
| [DrawType](../../groupdocs.conversion.options.load/cadloadoptions/drawtype) { get; set; } | Haalt of stelt het type tekening in. |
| [Format](../../groupdocs.conversion.options.load/cadloadoptions/format) { get; set; } | Invoerdocument bestandstype. Is `null` totdat een formaat is ingesteld, dus test op `null` in plaats van tegen [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), waaraan het nooit gelijk is. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Invoerdocument bestandstype. |
| [LayoutNames](../../groupdocs.conversion.options.load/cadloadoptions/layoutnames) { get; set; } | Specificeert welke CAD-indelingen moeten worden geconverteerd |
| [LayoutScope](../../groupdocs.conversion.options.load/cadloadoptions/layoutscope) { get; set; } | Haalt of stelt in welke tekenruimtes worden geconverteerd. Standaard is [`Both`](../cadlayoutscope/both), wat de conversie niet beperkt. Het wordt genegeerd wanneer [`LayoutNames`](./layoutnames) wordt opgegeven, omdat expliciete indelingsnamen altijd prevaleren. Een `null`-waarde wordt behandeld als [`Both`](../cadlayoutscope/both). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
