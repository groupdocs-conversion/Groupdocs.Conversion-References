---
title: "VectorizationOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor het vectoriseren van afbeeldingen."
type: docs
weight: 2900
url: /nl/net/groupdocs.conversion.options.load/vectorizationoptions/
---
## VectorizationOptions class

Opties voor het vectoriseren van afbeeldingen.

```csharp
public class VectorizationOptions : ValueObject
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [VectorizationOptions](vectorizationoptions)() | Standaardconstructor voor VectorizationOptions. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/vectorizationoptions/backgroundcolor) { get; set; } | Haalt op of stelt de achtergrondkleur in. Standaardwaarde is transparante wit. |
| [ColorsLimit](../../groupdocs.conversion.options.load/vectorizationoptions/colorslimit) { get; set; } | Haalt op of stelt het maximale aantal kleuren in dat wordt gebruikt om een afbeelding te kwantiseren. Standaardwaarde is 25. |
| [EnableVectorization](../../groupdocs.conversion.options.load/vectorizationoptions/enablevectorization) { get; set; } | Schakel vectorisatie van afbeeldingen in. Standaard is false. |
| [ImageSizeLimit](../../groupdocs.conversion.options.load/vectorizationoptions/imagesizelimit) { get; set; } | Haalt op of stelt de maximale afmeting van de afbeelding in, bepaald door de vermenigvuldiging van breedte en hoogte. De grootte van de afbeelding wordt geschaald op basis van deze eigenschap. Standaardwaarde is 1800000. |
| [LineWidth](../../groupdocs.conversion.options.load/vectorizationoptions/linewidth) { get; set; } | Haalt op of stelt de lijndikte in. De waarde van deze parameter wordt beïnvloed door de grafiekschaal. Standaardwaarde is 1. |
| [Severity](../../groupdocs.conversion.options.load/vectorizationoptions/severity) { get; set; } | Stelt de ernst van de afbeeldingstracering gladstrijken in |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
