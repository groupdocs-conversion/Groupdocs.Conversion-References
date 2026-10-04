---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Definieert Pdf-optimalisatieopties."
type: docs
weight: 2120
url: /nl/net/groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
## PdfOptimizationOptions class

Definieert Pdf-optimalisatieopties.

```csharp
public sealed class PdfOptimizationOptions : ValueObject
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Initialiseert een nieuwe instantie van de [`PdfOptimizationOptions`](../pdfoptimizationoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CompressImages](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/compressimages) { get; set; } | Als CompressImages is ingesteld op `true`, worden alle afbeeldingen in het document opnieuw gecomprimeerd. De compressie wordt bepaald door de ImageQuality‑eigenschap. |
| [FontSubsetStrategy](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/fontsubsetstrategy) { get; set; } | Stel lettertype‑subsetstrategie in |
| [ImageQuality](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/imagequality) { get; set; } | Waarde in procent, waarbij 100 % gelijk staat aan ongewijzigde kwaliteit en afbeeldingsgrootte. Om de afbeeldingsgrootte te verkleinen, stel deze eigenschap in op minder dan 100 |
| [LinkDuplicateStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/linkduplicatestreams) { get; set; } | Koppel dubbele streams |
| [RemoveUnusedObjects](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedobjects) { get; set; } | Verwijder ongebruikte objecten |
| [RemoveUnusedStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedstreams) { get; set; } | Verwijder ongebruikte streams |
| [UnembedFonts](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/unembedfonts) { get; set; } | Zet lettertypen niet ingesloten als dit op `true` staat |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
