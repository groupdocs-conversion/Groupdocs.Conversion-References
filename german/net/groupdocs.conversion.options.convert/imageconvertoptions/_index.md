---
title: ImageConvertOptions
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Optionen für die Konvertierung in den Bilddateityp.
type: docs
weight: 1470
url: /de/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Optionen für die Konvertierung in den Bilddateityp.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Initialisiert eine neue Instanz von[`ImageConvertOptions`](../imageconvertoptions) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Legt die Hintergrundfarbe fest, sofern vom Quellformat unterstützt |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Passt die Bildhelligkeit an. |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Passt den Bildkontrast an. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Bildumkehrmodus. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Der gewünschte Dateityp, in den das Eingabedokument konvertiert werden soll. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Der gewünschte Dateityp, in den das Eingabedokument konvertiert werden soll. |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Passt den Bild-Gammawert an. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Gibt an, ob in ein Graustufenbild konvertiert werden soll. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Gewünschte Bildhöhe nach Konvertierung. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Gewünschte horizontale Auflösung des Bildes nach der Konvertierung. Die Standardauflösung ist die Auflösung der Eingabedatei oder 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Jpeg-spezifische Konvertierungsoptionen. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Die Seitenzahl, ab der die Konvertierung beginnen soll. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Die Liste der zu konvertierenden Seitenindizes. Sollte angegeben werden, um bestimmte Seiten zu konvertieren. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Anzahl der zu konvertierenden Seiten ab`Seitennummer` . |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Psd-spezifische Konvertierungsoptionen. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Bildrotationswinkel. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Tiff-spezifische Konvertierungsoptionen. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Wenn`Stimmt` die Eingabe wird zuerst in PDF und danach in das gewünschte Format konvertiert. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Gewünschte vertikale Bildauflösung nach der Konvertierung. Die Standardauflösung ist die Auflösung der Eingabedatei oder 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Wasserzeichenspezifische Optionen |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Webp-spezifische Konvertierungsoptionen. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Gewünschte Bildbreite nach Konvertierung. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klont die aktuelle Optionsinstanz. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als Standard-Hash-Funktion. |

### Siehe auch

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* namensraum [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* Montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
