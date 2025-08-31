---
title: WordProcessingConvertOptions
second_title: GroupDocs.Conversion for .NET API Reference
description: Options for conversion to WordProcessing file type.
type: docs
weight: 2290
url: /net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

Options for conversion to WordProcessing file type.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IDpiConvertOptions, IPageMarginConvertOptions, IPageOrientationConvertOptions, 
    IPageSizeConvertOptions, IPasswordConvertOptions, IPdfRecognitionModeOptions, 
    IZoomConvertOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | Initializes new instance of [`WordProcessingConvertOptions`](../wordprocessingconvertoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | Desired page DPI after conversion. The default resolution is: 96 dpi. |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallbackpagesize) { get; set; } | Fallback page size |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | The desired file type the input document should be converted to. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implements [`Format`](../iconvertoptions/format) |
| [MarginBottom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginbottom) { get; set; } | Implements [`MarginBottom`](../ipagemarginconvertoptions/marginbottom) |
| [MarginLeft](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginleft) { get; set; } | Implements [`MarginLeft`](../ipagemarginconvertoptions/marginleft) |
| [MarginRight](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginright) { get; set; } | Implements [`MarginRight`](../ipagemarginconvertoptions/marginright) |
| [MarginTop](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/margintop) { get; set; } | Implements [`MarginTop`](../ipagemarginconvertoptions/margintop) |
| [MarkdownOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdownoptions) { get; set; } | Implements [`MarkdownOptions`](./markdownoptions) |
| [PageHeight](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pageheight) { get; set; } | Page height in points. When set, [`PageSize`](./pagesize) is automatically changed to [`Custom`](../pagesize/custom). |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implements [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [PageOrientation](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pageorientation) { get; set; } | Implements [`PageOrientation`](../ipageorientationconvertoptions/pageorientation) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implements [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implements [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pagesize) { get; set; } | Implements [`PageSize`](../ipagesizeconvertoptions/pagesize) |
| [PageWidth](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pagewidth) { get; set; } | Page width in points. When set, [`PageSize`](./pagesize) is automatically changed to [`Custom`](../pagesize/custom). |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | Set this property if you want to protect the converted document with a password. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | Implements [`PdfRecognitionMode`](../ipdfrecognitionmodeoptions/pdfrecognitionmode) |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | RTF specific convert options |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implements [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | Specifies the zoom level in percentage. Default is 100. Default zoom is supported till Microsoft Word 2010. Starting from Microsoft Word 2013 default zoom is no longer set to document, instead it appears to use the zoom factor of the last document that was opened. |

## Methods

| Name | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clones current options instance. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determines whether two object instances are equal. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Serves as the default hash function. |

### See Also

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IDpiConvertOptions](../idpiconvertoptions)
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
