---
title: PdfConvertOptions
second_title: GroupDocs.Conversion for .NET API Referens
description: Alternativ för konvertering till Pdffiltyp.
type: docs
weight: 1730
url: /sv/net/groupdocs.conversion.options.convert/pdfconvertoptions/
---
## PdfConvertOptions class

Alternativ för konvertering till Pdf-filtyp.

```csharp
public class PdfConvertOptions : CommonConvertOptions<PdfFileType>, IPageMarginConvertOptions, 
    IPageOrientationConvertOptions, IPageSizeConvertOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfConvertOptions](pdfconvertoptions)() | Initierar ny instans av[`PdfConvertOptions`](../pdfconvertoptions) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/pdfconvertoptions/dpi) { get; set; } | Önskad sida DPI efter konvertering. Standardupplösningen är: 96 dpi. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| [Height](../../groupdocs.conversion.options.convert/pdfconvertoptions/height) { get; set; } | Önskad sidhöjd i pixlar efter konvertering. |
| [MarginBottom](../../groupdocs.conversion.options.convert/pdfconvertoptions/marginbottom) { get; set; } | Önskad bottenmarginal på sidan i pixlar efter konvertering. |
| [MarginLeft](../../groupdocs.conversion.options.convert/pdfconvertoptions/marginleft) { get; set; } | Önskad vänstermarginal i pixlar efter konvertering. |
| [MarginRight](../../groupdocs.conversion.options.convert/pdfconvertoptions/marginright) { get; set; } | Önskad högermarginal på sidan i pixlar efter konvertering. |
| [MarginTop](../../groupdocs.conversion.options.convert/pdfconvertoptions/margintop) { get; set; } | Önskad toppmarginal på sidan i pixlar efter konvertering. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Sidnumret att börja konverteringen från. |
| [PageOrientation](../../groupdocs.conversion.options.convert/pdfconvertoptions/pageorientation) { get; set; } | Önskad sidorientering efter konvertering |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Listan över sidindex som ska konverteras. Bör specificeras för att konvertera specifika sidor. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Antal sidor att konvertera från`Sidonummer` . |
| [PageSize](../../groupdocs.conversion.options.convert/pdfconvertoptions/pagesize) { get; set; } | Önskad sidstorlek efter konvertering |
| [Password](../../groupdocs.conversion.options.convert/pdfconvertoptions/password) { get; set; } | Ange den här egenskapen om du vill skydda det konverterade dokumentet med ett lösenord. |
| [PdfOptions](../../groupdocs.conversion.options.convert/pdfconvertoptions/pdfoptions) { get; set; } | Pdf-specifika konverteringsalternativ |
| [Rotate](../../groupdocs.conversion.options.convert/pdfconvertoptions/rotate) { get; set; } | Sidrotation |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Vattenstämpelspecifika alternativ |
| [Width](../../groupdocs.conversion.options.convert/pdfconvertoptions/width) { get; set; } | Önskad sidbredd i pixlar efter konvertering. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klonar nuvarande alternativinstans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standard hash-funktion. |

### Se även

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PdfFileType](../../groupdocs.conversion.filetypes/pdffiletype)
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* namnutrymme [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
