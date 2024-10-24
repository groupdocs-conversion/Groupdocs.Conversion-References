---
title: FontFileType
second_title: GroupDocs.Conversion for .NET API Reference
description: Defines Font documents Includes the following types Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Learn more about Font formats herehttps//docs.fileformat.com/font/.
type: docs
weight: 970
url: /net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Defines Font documents Includes the following types: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Learn more about Font formats [here](https://docs.fileformat.com/font/).

```csharp
public sealed class FontFileType : FileType
```

## Constructors

| Name | Description |
| --- | --- |
| [FontFileType](fontfiletype)() | Serialization constructor |

## Properties

| Name | Description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | File type description |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | The file extension |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | The file family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | The file format |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compares current object to other. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implements [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Serves as the default hash function. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | String representation |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | A file with .cff extension is a Compact Font Format and is also known as a PostScript Type 1, or CIDFont. CFF acts as a container to store multiple fonts together in a single unit known as a FontSet. Learn more about this file format [here](https://docs.fileformat.com/font/cff/). |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | A file with .eot extension is an OpenType font that is embedded in a document. These are mostly used in web files such as a Web page. It was created by Microsoft and is supported by Microsoft Products including PowerPoint presentation .pps file. Learn more about this file format [here](https://docs.fileformat.com/font/eot/). |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | A file with .otf extension refers to OpenType font format. OTF font format is more scalable and extends the existing features of TTF formats for digital typography. Developed by Microsoft and Adobe, OTF combines the features of PostScript and TrueType font formats. Learn more about this file format [here](https://docs.fileformat.com/font/otf/). |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | A file with .ttf extension represents font files based on the TrueType specifications font technology. It was initially designed and launched by Apple Computer, Inc for Mac OS and was later adopted by Microsoft for Windows OS. Learn more about this file format [here](https://docs.fileformat.com/font/ttf/). |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Type 1 fonts is a deprecated Adobe technology which was widely used in the desktop based publishing software and printers that could use PostScript. Although Type 1 fonts are not supported in many modern platforms, web browsers and mobile operating systems, but these are still supported in some of the operating systems. Learn more about this file format [here](https://docs.fileformat.com/font/type1/). |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | A file with .woff extension is a web font file based on the Web Open Font Format (WOFF). It has format-specific compressed container based on either TrueType (.TTF) or OpenType (.OTT) font types. Learn more about this file format [here](https://docs.fileformat.com/font/woff/). |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | A file with .woff extension is a web font file based on the Web Open Font Format (WOFF). It has format-specific compressed container based on either TrueType (.TTF) or OpenType (.OTT) font types. Learn more about this file format [here](https://docs.fileformat.com/font/woff/). |

### See Also

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
