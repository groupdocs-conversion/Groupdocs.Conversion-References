---
title: PdfOptimizationOptions
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Definieert pdfoptimalisatieopties.
type: docs
weight: 1780
url: /nl/net/groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
## PdfOptimizationOptions class

Definieert pdf-optimalisatie-opties.

```csharp
public sealed class PdfOptimizationOptions : ValueObject
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Initialiseert nieuw exemplaar van[`PdfOptimizationOptions`](../pdfoptimizationoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CompressImages](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/compressimages) { get; set; } | Als CompressImages is ingesteld op`WAAR` , worden alle afbeeldingen in het document opnieuw gecomprimeerd. De compressie wordt bepaald door de eigenschap ImageQuality. |
| [ImageQuality](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/imagequality) { get; set; } | Waarde in procenten waarbij 100% gelijk is aan ongewijzigde kwaliteit en afbeeldingsgrootte. Als u de afbeeldingsgrootte wilt verkleinen, stelt u deze eigenschap in op minder dan 100 |
| [LinkDuplicateStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/linkduplicatestreams) { get; set; } | Koppel dubbele streams |
| [RemoveUnusedObjects](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedobjects) { get; set; } | Ongebruikte objecten verwijderen |
| [RemoveUnusedStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedstreams) { get; set; } | Verwijder ongebruikte streams |
| [UnembedFonts](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/unembedfonts) { get; set; } | Maak lettertypen niet ingesloten indien ingesteld op true |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* naamruimte [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->