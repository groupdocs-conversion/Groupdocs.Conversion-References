---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Definierar PDF-optimeringsalternativ."
type: docs
weight: 2120
url: /sv/net/groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
## PdfOptimizationOptions class

Definierar PDF-optimeringsalternativ.

```csharp
public sealed class PdfOptimizationOptions : ValueObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Initierar en ny instans av [`PdfOptimizationOptions`](../pdfoptimizationoptions) klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CompressImages](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/compressimages) { get; set; } | Om CompressImages är satt till `true` komprimeras alla bilder i dokumentet om. Komprimeringen definieras av egenskapen ImageQuality. |
| [FontSubsetStrategy](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/fontsubsetstrategy) { get; set; } | Ange teckensnittssubsetstrategi |
| [ImageQuality](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/imagequality) { get; set; } | Värde i procent där 100 % är oförändrad kvalitet och bildstorlek. För att minska bildstorleken, sätt denna egenskap till mindre än 100. |
| [LinkDuplicateStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/linkduplicatestreams) { get; set; } | Länka duplicerade strömmar |
| [RemoveUnusedObjects](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedobjects) { get; set; } | Ta bort oanvända objekt |
| [RemoveUnusedStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedstreams) { get; set; } | Ta bort oanvända strömmar |
| [UnembedFonts](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/unembedfonts) { get; set; } | Gör så att teckensnitt inte bäddas in om satt till true |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
