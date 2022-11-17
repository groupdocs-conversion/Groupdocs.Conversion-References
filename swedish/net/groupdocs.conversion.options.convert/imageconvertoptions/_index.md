---
title: ImageConvertOptions
second_title: GroupDocs.Conversion for .NET API Referens
description: Alternativ för konvertering till bildfiltyp.
type: docs
weight: 1470
url: /sv/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Alternativ för konvertering till bildfiltyp.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Initierar ny instans av[`ImageConvertOptions`](../imageconvertoptions) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Anger bakgrundsfärg där det stöds av källformatet |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Justerar bildens ljusstyrka. |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Justerar bildens kontrast. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Bildvändningsläge. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Justerar bildgamma. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Indikerar om det ska konverteras till gråskalebild. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Önskad bildhöjd efter konvertering. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Önskad horisontell bildupplösning efter konvertering. Standardupplösningen är indatafilens upplösning eller 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Jpeg-specifika konverteringsalternativ. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Sidnumret att börja konverteringen från. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Listan över sidindex som ska konverteras. Bör specificeras för att konvertera specifika sidor. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Antal sidor att konvertera från`Sidonummer` . |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Psd-specifika konverteringsalternativ. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Bildrotationsvinkel. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Tiff-specifika konverteringsalternativ. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Om`Sann` indata konverteras först till PDF och därefter till önskat format. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Önskad vertikal bildupplösning efter konvertering. Standardupplösningen är indatafilens upplösning eller 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Vattenstämpelspecifika alternativ |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Webp-specifika konverteringsalternativ. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Önskad bildbredd efter konvertering. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klonar nuvarande alternativinstans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standard hash-funktion. |

### Se även

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* namnutrymme [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
