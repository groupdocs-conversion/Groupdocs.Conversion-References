---
title: FontFileType
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Defines Font documents.
type: docs
weight: 17
url: /nodejs-java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

Defines Font documents. Includes the following types: [Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype\#Ttf), [Eot](../../com.groupdocs.conversion.filetypes/fontfiletype\#Eot), [Otf](../../com.groupdocs.conversion.filetypes/fontfiletype\#Otf), [Cff](../../com.groupdocs.conversion.filetypes/fontfiletype\#Cff), [Type1](../../com.groupdocs.conversion.filetypes/fontfiletype\#Type1), [Woff](../../com.groupdocs.conversion.filetypes/fontfiletype\#Woff), [Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype\#Woff2), Learn more about Font formats [here][].


[here]: https://wiki.fileformat.com/font
## Constructors

| Constructor | Description |
| --- | --- |
| [FontFileType()](#FontFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [Ttf](#Ttf) | A file with .ttf extension represents font files based on the TrueType specifications font technology. |
| [Eot](#Eot) | A file with .eot extension is an OpenType font that is embedded in a document. |
| [Otf](#Otf) | A file with .otf extension refers to OpenType font format. |
| [Cff](#Cff) | A file with .cff extension is a Compact Font Format and is also known as a PostScript Type 1, or CIDFont. |
| [Type1](#Type1) | Type 1 fonts is a deprecated Adobe technology which was widely used in the desktop based publishing software and printers that could use PostScript. |
| [Woff](#Woff) | A file with .woff extension is a web font file based on the Web Open Font Format (WOFF). |
| [Woff2](#Woff2) | A file with .woff extension is a web font file based on the Web Open Font Format (WOFF). |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### FontFileType() {#FontFileType--}
```
public FontFileType()
```


Serialization constructor

### Ttf {#Ttf}
```
public static final FontFileType Ttf
```


A file with .ttf extension represents font files based on the TrueType specifications font technology. It was initially designed and launched by Apple Computer, Inc for Mac OS and was later adopted by Microsoft for Windows OS. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/font/ttf/

### Eot {#Eot}
```
public static final FontFileType Eot
```


A file with .eot extension is an OpenType font that is embedded in a document. These are mostly used in web files such as a Web page. It was created by Microsoft and is supported by Microsoft Products including PowerPoint presentation .pps file. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/font/eot/

### Otf {#Otf}
```
public static final FontFileType Otf
```


A file with .otf extension refers to OpenType font format. OTF font format is more scalable and extends the existing features of TTF formats for digital typography. Developed by Microsoft and Adobe, OTF combines the features of PostScript and TrueType font formats. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/font/otf/

### Cff {#Cff}
```
public static final FontFileType Cff
```


A file with .cff extension is a Compact Font Format and is also known as a PostScript Type 1, or CIDFont. CFF acts as a container to store multiple fonts together in a single unit known as a FontSet. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/font/cff/

### Type1 {#Type1}
```
public static final FontFileType Type1
```


Type 1 fonts is a deprecated Adobe technology which was widely used in the desktop based publishing software and printers that could use PostScript. Although Type 1 fonts are not supported in many modern platforms, web browsers and mobile operating systems, but these are still supported in some of the operating systems. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/font/type1/

### Woff {#Woff}
```
public static final FontFileType Woff
```


A file with .woff extension is a web font file based on the Web Open Font Format (WOFF). It has format-specific compressed container based on either TrueType (.TTF) or OpenType (.OTT) font types. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/font/woff/

### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


A file with .woff extension is a web font file based on the Web Open Font Format (WOFF). It has format-specific compressed container based on either TrueType (.TTF) or OpenType (.OTT) font types. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/font/woff/

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Prepared default load options for the source file type

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Prepared default convert options for the file type

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
