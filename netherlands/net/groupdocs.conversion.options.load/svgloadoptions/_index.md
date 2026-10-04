---
title: "SvgLoadOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor het laden van Svg-documenten."
type: docs
weight: 2830
url: /nl/net/groupdocs.conversion.options.load/svgloadoptions/
---
## SvgLoadOptions class

Opties voor het laden van Svg-documenten.

```csharp
public class SvgLoadOptions : LoadOptions, IResourceLoadingOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SvgLoadOptions](svgloadoptions)() | Initialiseert een nieuw exemplaar van de [`SvgLoadOptions`](../svgloadoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CropToContentBounds](../../groupdocs.conversion.options.load/svgloadoptions/croptocontentbounds) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of de SVG-boundingbox moet worden bijgesneden tot de inhoudsgrenzen vóór conversie. Standaard is false. |
| [Format](../../groupdocs.conversion.options.load/svgloadoptions/format) { get; set; } | Invoerdocument bestandstype. Is `null` totdat een formaat is ingesteld, dus test op `null` in plaats van tegen [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), waaraan het nooit gelijk is. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Invoerdocument bestandstype. |
| [MinimumHeight](../../groupdocs.conversion.options.load/svgloadoptions/minimumheight) { get; set; } | Stel de minimale hoogte in voor het converteren van een SVG-document. Deze wordt gebruikt bij conversie naar rasterformaten. Standaard is 600. |
| [MinimumWidth](../../groupdocs.conversion.options.load/svgloadoptions/minimumwidth) { get; set; } | Stel de minimale breedte in voor het converteren van een SVG-document. Deze wordt gebruikt bij conversie naar rasterformaten. Standaard is 800. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/svgloadoptions/skipexternalresources) { get; set; } | Implementeert [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/svgloadoptions/whitelistedresources) { get; set; } | Externe bronnen die altijd worden geladen. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [LoadOptions](../loadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
