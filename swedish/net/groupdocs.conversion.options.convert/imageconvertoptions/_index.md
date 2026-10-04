---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för konvertering till Image-filtyp."
type: docs
weight: 1950
url: /sv/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Alternativ för konvertering till Image-filtyp.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Initierar en ny instans av [`ImageConvertOptions`](../imageconvertoptions) klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Ställer in bakgrundsfärg där det stöds av källformatet |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Justerar bildens ljusstyrka. |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | När den är inställd begränsar den PDF-renderingsupplösningen per sida till sidans inhemska rasterupplösning så att en sida aldrig renderas med en högre DPI än den inbäddade bilden faktiskt har, och skickar ut den sidan med dess inhemska (mindre) pixelmått och inhemska DPI i det slutliga resultatet istället för att förstora den till den begärda DPI:n. Endast bilddominerade (skannade) sidor påverkas; sidor med text eller vektorinnehåll mjukas aldrig och skickas ut med den begärda DPI:n. Hoppar över när en explicit utdata [`Width`](./width) eller [`Height`](./height) är angiven. Standardvärdet är `false` (ingen begränsning; varje sida renderas och skickas ut med den begärda DPI:n). |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Justerar bildkontrast. |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | Beskär rasterbildens område efter konvertering |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Bildvändningsläge. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementerar [`Format`](../iconvertoptions/format) |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Justerar bildens gamma. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Anger om bilden ska konverteras till gråskala. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Önskad bildhöjd efter konvertering. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Önskad horisontell bildupplösning efter konvertering. Standardupplösningen är upplösningen i indatafilen eller 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Jpeg-specifika konverteringsalternativ. |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | Per-axel nedre gräns som tillämpas på den begränsade renderings-DPI:n när [`CapResolutionToPageContent`](./capresolutiontopagecontent) är aktiverad. Den begränsade DPI:n sänks aldrig under detta värde. Standardvärdet är `0` (ingen golvgräns). |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementerar [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementerar [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementerar [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Psd-specifika konverteringsalternativ. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Bildrotationsvinkel. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Tiff-specifika konverteringsalternativ. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Om `true` konverteras först indata till PDF och därefter till önskat format. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Önskad vertikal bildupplösning efter konvertering. Standardupplösningen är upplösningen i indatafilen eller 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementerar [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Webp-specifika konverteringsalternativ. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Önskad bildbredd efter konvertering. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klonar aktuell alternativinstans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
