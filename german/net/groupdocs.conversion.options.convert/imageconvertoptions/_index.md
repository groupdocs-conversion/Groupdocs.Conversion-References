---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Optionen für die Konvertierung zum Bilddateityp."
type: docs
weight: 1950
url: /de/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Optionen für die Konvertierung zum Bilddateityp.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Initialisiert eine neue Instanz der [`ImageConvertOptions`](../imageconvertoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Legt die Hintergrundfarbe fest, sofern vom Quellformat unterstützt. |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Passt die Bildhelligkeit an. |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | Wenn aktiviert, begrenzt sie die Renderauflösung pro PDF‑Seite auf die native Rasterauflösung der Seite, sodass eine Seite niemals mit einer höheren DPI gerendert wird, als das eingebettete Bild tatsächlich enthält, und gibt diese Seite in ihrer nativen (kleineren) Pixelgröße und nativen DPI in der endgültigen Ausgabe aus, anstatt sie auf die gewünschte DPI hochzuskalieren. Nur bilddominierte (Scan‑)Seiten sind betroffen; Seiten mit Text‑ oder Vektorinhalt werden niemals weichgezeichnet und werden mit der gewünschten DPI ausgegeben. Wird übersprungen, wenn ein expliziter Ausgabewert für [`Width`](./width) oder [`Height`](./height) festgelegt ist. Der Standardwert ist `false` (keine Begrenzung; jede Seite wird mit der gewünschten DPI gerendert und ausgegeben). |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Passt den Bildkontrast an. |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | Beschneidet den Rasterbildbereich nach der Konvertierung. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Bildspiegelungsmodus. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Der gewünschte Dateityp, in den das Eingabedokument konvertiert werden soll. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementiert [`Format`](../iconvertoptions/format) |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Passt das Bild‑Gamma an. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Gibt an, ob in ein Graustufenbild konvertiert werden soll. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Gewünschte Bildhöhe nach der Konvertierung. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Gewünschte horizontale Bildauflösung nach der Konvertierung. Die Standardauflösung ist die Auflösung der Eingabedatei oder 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Jpeg‑spezifische Konvertierungsoptionen. |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | Achsenweise Untergrenze, die auf die begrenzte Render‑DPI angewendet wird, wenn [`CapResolutionToPageContent`](./capresolutiontopagecontent) aktiviert ist. Die begrenzte DPI wird niemals unter diesen Wert gesenkt. Der Standardwert ist `0` (keine Untergrenze). |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementiert [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementiert [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementiert [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Psd‑spezifische Konvertierungsoptionen. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Bilddrehwinkel. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Tiff‑spezifische Konvertierungsoptionen. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Wenn `true`, wird die Eingabe zuerst in PDF konvertiert und danach in das gewünschte Format. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Gewünschte vertikale Bildauflösung nach der Konvertierung. Die Standardauflösung ist die Auflösung der Eingabedatei oder 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementiert [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Webp‑spezifische Konvertierungsoptionen. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Gewünschte Bildbreite nach der Konvertierung. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klonen der aktuellen Optionsinstanz. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als Standard-Hashfunktion. |

### Siehe auch

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
