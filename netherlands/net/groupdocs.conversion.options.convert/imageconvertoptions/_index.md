---
title: ImageConvertOptions
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Opties voor conversie naar afbeeldingsbestandstype.
type: docs
weight: 1630
url: /nl/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Opties voor conversie naar afbeeldingsbestandstype.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Initialiseert nieuw exemplaar van[`ImageConvertOptions`](../imageconvertoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Stelt de achtergrondkleur in waar ondersteund door het bronformaat |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Past de helderheid van het beeld aan. |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Past het beeldcontrast aan. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Afbeelding omdraaien-modus. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Past beeldgamma aan. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Geeft aan of moet worden geconverteerd naar afbeelding in grijstinten. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Gewenste beeldhoogte na conversie. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Gewenste horizontale afbeeldingsresolutie na conversie. De standaardresolutie is de resolutie van het invoerbestand of 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | JPEG-specifieke conversie-opties. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Het paginanummer vanaf waar de conversie moet worden gestart. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | De lijst met pagina-indexen die moeten worden geconverteerd. Moet worden opgegeven om specifieke pagina's te converteren. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Aantal pagina's om vanaf te converteren`Paginanummer` . |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Psd-specifieke conversie-opties. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Beeldrotatiehoek. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Tiff-specifieke conversieopties. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Als`WAAR` , wordt de invoer eerst geconverteerd naar PDF en daarna naar het gewenste formaat. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Gewenste verticale beeldresolutie na conversie. De standaardresolutie is de resolutie van het invoerbestand of 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Watermerkspecifieke opties |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Webp-specifieke conversieopties. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Gewenste beeldbreedte na conversie. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Kloont de huidige optie-instantie. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* naamruimte [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
