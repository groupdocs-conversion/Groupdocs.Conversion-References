---
title: "PdfOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för konvertering till PDF-filtyp."
type: docs
weight: 2130
url: /sv/net/groupdocs.conversion.options.convert/pdfoptions/
---
## PdfOptions class

Alternativ för konvertering till PDF-filtyp.

```csharp
public sealed class PdfOptions : ValueObject, IZoomConvertOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfOptions](pdfoptions)() | Initierar en ny instans av klassen [`PdfOptions`](../pdfoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DocumentInfo](../../groupdocs.conversion.options.convert/pdfoptions/documentinfo) { get; set; } | Metainformation för PDF-dokument. |
| [FormattingOptions](../../groupdocs.conversion.options.convert/pdfoptions/formattingoptions) { get; set; } | PDF-formateringsalternativ |
| [Grayscale](../../groupdocs.conversion.options.convert/pdfoptions/grayscale) { get; set; } | Konvertera en PDF från RGB-färgrymd till gråskala |
| [Linearize](../../groupdocs.conversion.options.convert/pdfoptions/linearize) { get; set; } | Lineariserar PDF-dokument för webben |
| [OptimizationOptions](../../groupdocs.conversion.options.convert/pdfoptions/optimizationoptions) { get; set; } | PDF-optimeringsalternativ |
| [PdfFormat](../../groupdocs.conversion.options.convert/pdfoptions/pdfformat) { get; set; } | Ställer in PDF-formatet för det konverterade dokumentet. |
| [RemovePdfACompliance](../../groupdocs.conversion.options.convert/pdfoptions/removepdfacompliance) { get; set; } | Tar bort PDF/A-efterlevnad |
| [Zoom](../../groupdocs.conversion.options.convert/pdfoptions/zoom) { get; set; } | Anger zoomnivån i procent. Standard är 100. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
