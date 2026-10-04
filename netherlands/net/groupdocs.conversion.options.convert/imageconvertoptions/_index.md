---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor conversie naar afbeeldingsbestandtype."
type: docs
weight: 1950
url: /nl/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Opties voor conversie naar afbeeldingsbestandtype.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Initialiseert een nieuwe instantie van de [`ImageConvertOptions`](../imageconvertoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Stelt de achtergrondkleur in waar ondersteund door het bronformaat. |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Past de helderheid van de afbeelding aan. |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | Indien ingesteld, wordt de renderresolutie per pagina van de PDF beperkt tot de native rasterresolutie van de pagina, zodat een pagina nooit wordt gerenderd op een hogere DPI dan de ingesloten afbeelding daadwerkelijk bevat, en wordt die pagina uitgegeven met zijn native (kleinere) pixelafmetingen en native DPI in de uiteindelijke output in plaats van deze op te blazen naar de gevraagde DPI. Alleen paginabeelden die voornamelijk uit afbeeldingen bestaan (scan) worden beïnvloed; pagina's met tekst of vectorinhoud worden nooit verzacht en worden uitgegeven met de gevraagde DPI. Wordt overgeslagen wanneer een expliciete uitvoer [`Width`](./width) of [`Height`](./height) is ingesteld. De standaardwaarde is `false` (geen beperking; elke pagina wordt gerenderd en uitgegeven met de gevraagde DPI). |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Past het contrast van de afbeelding aan. |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | Snijd rasterafbeeldingsgebied bij na conversie |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Afbeelding spiegelmodus. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementeert [`Format`](../iconvertoptions/format) |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Past de gamma van de afbeelding aan. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Geeft aan of er moet worden geconverteerd naar een grijswaardenafbeelding. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Gewenste afbeeldinghoogte na conversie. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Gewenste horizontale resolutie van de afbeelding na conversie. De standaardresolutie is de resolutie van het invoerbestand of 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Jpeg-specifieke conversie‑opties. |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | Per-as ondergrens toegepast op de begrensde render DPI wanneer [`CapResolutionToPageContent`](./capresolutiontopagecontent) is ingeschakeld. De begrensde DPI wordt nooit lager dan deze waarde ingesteld. Standaard is `0` (geen ondergrens). |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementeert [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementeert [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementeert [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Psd-specifieke conversie‑opties. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Afbeeldingsrotatiehoek. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Tiff-specifieke conversie‑opties. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Als `true`, wordt de invoer eerst naar PDF geconverteerd en daarna naar het gewenste formaat |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Gewenste verticale resolutie van de afbeelding na conversie. De standaardresolutie is de resolutie van het invoerbestand of 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementeert [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Webp-specifieke conversie‑opties. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Gewenste afbeeldingsbreedte na conversie. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Kloont de huidige opties-instantie. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
