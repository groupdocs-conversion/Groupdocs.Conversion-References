---
title: ImageConvertOptions
second_title: GroupDocs.Conversion for .NET API Reference
description: Options for conversion to Image file type.
type: docs
weight: 1890
url: /net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Options for conversion to Image file type.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Initializes new instance of [`ImageConvertOptions`](../imageconvertoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Sets background color where supported by the source format |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Adjusts image brightness. |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | When set, caps the per-page PDF render resolution to the page native raster resolution so a page is never rendered at a higher DPI than its embedded image actually contains, and emits that page at its native (smaller) pixel dimensions and native DPI in the final output instead of re-inflating it to the requested DPI. Only image-dominated (scan) pages are affected; pages with text or vector content are never softened and are emitted at the requested DPI. Skipped when an explicit output [`Width`](./width) or [`Height`](./height) is set. The default is `false` (no capping; every page is rendered and emitted at the requested DPI). |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Adjusts image contrast. |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | Crop raster image area after conversion |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Image flip mode. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | The desired file type the input document should be converted to. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implements [`Format`](../iconvertoptions/format) |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Adjusts image gamma. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Indicates whether to convert into grayscale image. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Desired image height after conversion. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Desired image horizontal resolution after conversion. The default resolution is the resolution of the input file or 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Jpeg specific convert options. |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | Per-axis lower bound applied to the capped render DPI when [`CapResolutionToPageContent`](./capresolutiontopagecontent) is enabled. The capped DPI is never lowered below this value. The default is `0` (no floor). |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implements [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implements [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implements [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Psd specific convert options. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Image rotation angle. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Tiff specific convert options. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | If `true`, the input firstly is converted to PDF and after that to desired format |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Desired image vertical resolution after conversion. The default resolution is the resolution of the input file or 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implements [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Webp specific convert options. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Desired image width after conversion. |

## Methods

| Name | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clones current options instance. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determines whether two object instances are equal. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Serves as the default hash function. |

### See Also

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
