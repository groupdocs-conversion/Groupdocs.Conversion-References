---
title: WordProcessingConvertOptions
second_title: GroupDocs.Conversion for .NET API Reference
description: Options for conversion to WordProcessing file type.
type: docs
weight: 1950
url: /net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

Options for conversion to WordProcessing file type.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IPageMarginConvertOptions, IPageOrientationConvertOptions, IPageSizeConvertOptions, 
    IPdfRecognitionModeOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | Initializes new instance of [`WordProcessingConvertOptions`](../wordprocessingconvertoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | Desired page DPI after conversion. The default resolution is: 96 dpi. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | The desired file type the input document should be converted to. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | The desired file type the input document should be converted to. |
| [Height](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/height) { get; set; } | Desired page height after conversion. |
| [MarginBottom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginbottom) { get; set; } | Desired page bottom margin in pixels after conversion. |
| [MarginLeft](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginleft) { get; set; } | Desired page left margin in pixels after conversion. |
| [MarginRight](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginright) { get; set; } | Desired page right margin in pixels after conversion. |
| [MarginTop](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/margintop) { get; set; } | Desired page top margin in pixels after conversion. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | The page number to start conversion from. |
| [PageOrientation](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pageorientation) { get; set; } | Desired page orientation after conversion |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | The list of page indexes to be converted. Should be specified to convert specific pages. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Number of pages to convert starting from `PageNumber`. |
| [PageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pagesize) { get; set; } | Desired page size after conversion |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | Set this property if you want to protect the converted document with a password. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | Recognition mode when converting from pdf |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | RTF specific convert options |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Watermark specific options |
| [Width](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/width) { get; set; } | Desired page width after conversion. |
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
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
