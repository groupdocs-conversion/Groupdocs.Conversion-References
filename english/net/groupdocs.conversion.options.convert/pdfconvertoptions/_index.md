---
title: PdfConvertOptions
second_title: GroupDocs.Conversion for .NET API Reference
description: Options for conversion to Pdf file type.
type: docs
weight: 2020
url: /net/groupdocs.conversion.options.convert/pdfconvertoptions/
---
## PdfConvertOptions class

Options for conversion to Pdf file type.

```csharp
public class PdfConvertOptions : CommonConvertOptions<PdfFileType>, IDpiConvertOptions, 
    IPageMarginConvertOptions, IPageOrientationConvertOptions, IPageSizeConvertOptions, 
    IPasswordConvertOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfConvertOptions](pdfconvertoptions)() | Initializes new instance of [`PdfConvertOptions`](../pdfconvertoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/pdfconvertoptions/dpi) { get; set; } | Desired page DPI after conversion. The default resolution is: 96 dpi. |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/pdfconvertoptions/fallbackpagesize) { get; set; } | Fallback page size |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | The desired file type the input document should be converted to. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implements [`Format`](../iconvertoptions/format) |
| [MarginBottom](../../groupdocs.conversion.options.convert/pdfconvertoptions/marginbottom) { get; set; } | Implements [`MarginBottom`](../ipagemarginconvertoptions/marginbottom) |
| [MarginLeft](../../groupdocs.conversion.options.convert/pdfconvertoptions/marginleft) { get; set; } | Implements [`MarginLeft`](../ipagemarginconvertoptions/marginleft) |
| [MarginRight](../../groupdocs.conversion.options.convert/pdfconvertoptions/marginright) { get; set; } | Implements [`MarginRight`](../ipagemarginconvertoptions/marginright) |
| [MarginTop](../../groupdocs.conversion.options.convert/pdfconvertoptions/margintop) { get; set; } | Implements [`MarginTop`](../ipagemarginconvertoptions/margintop) |
| [PageHeight](../../groupdocs.conversion.options.convert/pdfconvertoptions/pageheight) { get; set; } | Page height in points. When set, [`PageSize`](./pagesize) is automatically changed to [`Custom`](../pagesize/custom). |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implements [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [PageOrientation](../../groupdocs.conversion.options.convert/pdfconvertoptions/pageorientation) { get; set; } | Implements [`PageOrientation`](../ipageorientationconvertoptions/pageorientation) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implements [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implements [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PageSize](../../groupdocs.conversion.options.convert/pdfconvertoptions/pagesize) { get; set; } | Implements [`PageSize`](../ipagesizeconvertoptions/pagesize) |
| [PageWidth](../../groupdocs.conversion.options.convert/pdfconvertoptions/pagewidth) { get; set; } | Page width in points. When set, [`PageSize`](./pagesize) is automatically changed to [`Custom`](../pagesize/custom). |
| [Password](../../groupdocs.conversion.options.convert/pdfconvertoptions/password) { get; set; } | Set this property if you want to protect the converted document with a password. |
| [PdfOptions](../../groupdocs.conversion.options.convert/pdfconvertoptions/pdfoptions) { get; set; } | Pdf specific convert options |
| [Rotate](../../groupdocs.conversion.options.convert/pdfconvertoptions/rotate) { get; set; } | Page rotation |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implements [`Watermark`](../iwatermarkedconvertoptions/watermark) |

## Methods

| Name | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clones current options instance. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determines whether two object instances are equal. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Serves as the default hash function. |

### See Also

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PdfFileType](../../groupdocs.conversion.filetypes/pdffiletype)
* interface [IDpiConvertOptions](../idpiconvertoptions)
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
