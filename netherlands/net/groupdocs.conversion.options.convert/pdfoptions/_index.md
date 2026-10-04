---
title: "PdfOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor conversie naar PDF‑bestandtype."
type: docs
weight: 2130
url: /nl/net/groupdocs.conversion.options.convert/pdfoptions/
---
## PdfOptions class

Opties voor conversie naar PDF‑bestandtype.

```csharp
public sealed class PdfOptions : ValueObject, IZoomConvertOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PdfOptions](pdfoptions)() | Initialiseert een nieuw exemplaar van de [`PdfOptions`](../pdfoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [DocumentInfo](../../groupdocs.conversion.options.convert/pdfoptions/documentinfo) { get; set; } | Meta-informatie van PDF-document. |
| [FormattingOptions](../../groupdocs.conversion.options.convert/pdfoptions/formattingoptions) { get; set; } | Pdf-opmaakopties |
| [Grayscale](../../groupdocs.conversion.options.convert/pdfoptions/grayscale) { get; set; } | Converteer een PDF van RGB-kleurruimte naar grijswaarden |
| [Linearize](../../groupdocs.conversion.options.convert/pdfoptions/linearize) { get; set; } | Lineariseert PDF-document voor het web |
| [OptimizationOptions](../../groupdocs.conversion.options.convert/pdfoptions/optimizationoptions) { get; set; } | Pdf-optimalisatieoptjes |
| [PdfFormat](../../groupdocs.conversion.options.convert/pdfoptions/pdfformat) { get; set; } | Stelt het pdf-formaat van het geconverteerde document in. |
| [RemovePdfACompliance](../../groupdocs.conversion.options.convert/pdfoptions/removepdfacompliance) { get; set; } | Verwijdert Pdf-A-conformiteit |
| [Zoom](../../groupdocs.conversion.options.convert/pdfoptions/zoom) { get; set; } | Specificeert het zoomniveau in procenten. Standaard is 100. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
