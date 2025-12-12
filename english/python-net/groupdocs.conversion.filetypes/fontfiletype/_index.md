---
title: FontFileType class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.filetypes/fontfiletype/
is_root: false
weight: 90
---

## FontFileType class

Defines Font documents
Includes the following types:
[`FontFileType.Ttf`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype)[`FontFileType.Eot`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype)[`FontFileType.Otf`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype)[`FontFileType.Cff`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype)[`FontFileType.Type1`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype)[`FontFileType.Woff`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype)[`FontFileType.Woff2`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype)
Learn more about Font formats [here](https://docs.fileformat.com/font/).



**Inheritance:** [`FontFileType`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype) → 
[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype) → 
[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)



The FontFileType type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/__init__/#) | Serialization constructor |


### Properties
| Property | Description |
| :- | :- |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/file_format) | The file format |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/extension) | The file extension |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/family) | The file family |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/description) | File type description |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/unknown) | Unknown file type |
| [TTF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/ttf) | A file with .ttf extension represents font files based on the TrueType specifications font technology. It was initially designed and launched by Apple Computer, Inc for Mac OS and was later adopted by Microsoft for Windows OS.<br/>Learn more about this file format [here](https://docs.fileformat.com/font/ttf/). |
| [EOT](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/eot) | A file with .eot extension is an OpenType font that is embedded in a document. These are mostly used in web files such as a Web page. It was created by Microsoft and is supported by Microsoft Products including PowerPoint presentation .pps file.<br/>Learn more about this file format [here](https://docs.fileformat.com/font/eot/). |
| [OTF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/otf) | A file with .otf extension refers to OpenType font format. OTF font format is more scalable and extends the existing features of TTF formats for digital typography. Developed by Microsoft and Adobe, OTF combines the features of PostScript and TrueType font formats. <br/>Learn more about this file format [here](https://docs.fileformat.com/font/otf/). |
| [CFF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/cff) | A file with .cff extension is a Compact Font Format and is also known as a PostScript Type 1, or CIDFont. CFF acts as a container to store multiple fonts together in a single unit known as a FontSet. <br/>Learn more about this file format [here](https://docs.fileformat.com/font/cff/). |
| [TYPE1](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/type1) | Type 1 fonts is a deprecated Adobe technology which was widely used in the desktop based publishing software and printers that could use PostScript. Although Type 1 fonts are not supported in many modern platforms, web browsers and mobile operating systems, but these are still supported in some of the operating systems.<br/>Learn more about this file format [here](https://docs.fileformat.com/font/type1/). |
| [WOFF](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/woff) | A file with .woff extension is a web font file based on the Web Open Font Format (WOFF). It has format-specific compressed container based on either TrueType (.TTF) or OpenType (.OTT) font types.<br/>Learn more about this file format [here](https://docs.fileformat.com/font/woff/). |
| [WOFF2](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/woff2) | A file with .woff extension is a web font file based on the Web Open Font Format (WOFF). It has format-specific compressed container based on either TrueType (.TTF) or OpenType (.OTT) font types.<br/>Learn more about this file format [here](https://docs.fileformat.com/font/woff/). |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/equals/#groupdocs.conversion.contracts.Enumeration) | Implements [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals) |
| [compare_to](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/compare_to/#System.Object) | Compares current object to other. |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/from_filename/#System.String) | Returns FileType for specified fileName |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/from_extension/#System.String) | Gets FileType for provided fileExtension |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype/from_stream/#io.RawIOBase) | Returns FileType for provided document stream |



### See Also
* module [`groupdocs.conversion.filetypes`](..)
* class [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)
* class [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype)
* class [`FontFileType`](/conversion/python-net/groupdocs.conversion.filetypes/fontfiletype)
