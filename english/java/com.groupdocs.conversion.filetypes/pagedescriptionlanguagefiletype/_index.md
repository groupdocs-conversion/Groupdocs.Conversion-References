---
title: PageDescriptionLanguageFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines Page description documents.
type: docs
weight: 20
url: /java/com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PageDescriptionLanguageFileType extends FileType implements Serializable
```

Defines Page description documents. Includes the following types: [Svg](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Svg), [Eps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Eps), [Cgm](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Cgm), [Xps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Xps), [Tex](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Tex), [Ps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Ps), [Pcl](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Pcl), [Oxps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype\#Oxps),
## Constructors

| Constructor | Description |
| --- | --- |
| [PageDescriptionLanguageFileType()](#PageDescriptionLanguageFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [Svg](#Svg) | An SVG file is a Scalar Vector Graphics file that uses XML based text format for describing the appearance of an image. |
| [Eps](#Eps) | Files with EPS extension essentially describe an Encapsulated PostScript language program that describes the appearance of a single page. |
| [Cgm](#Cgm) | Computer Graphics Metafile (CGM) is free, platform-independent, international standard metafile format for storing and exchanging of vector graphics (2D), raster graphics, and text. |
| [Xps](#Xps) | An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. |
| [Tex](#Tex) | TeX is a language that comprises of programming as well as mark-up features, used to typeset documents. |
| [Ps](#Ps) | PostScript (PS) is a general-purpose page description language used in the business of desktop and electronic publishing. |
| [Pcl](#Pcl) | PCL stands for Printer Command Language which is a Page Description Language introduced by Hewlett Packard (HP). |
| [Oxps](#Oxps) | The file format OXPS is known as Open XML Paper Specification. |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PageDescriptionLanguageFileType() {#PageDescriptionLanguageFileType--}
```
public PageDescriptionLanguageFileType()
```


Serialization constructor

### Svg {#Svg}
```
public static final PageDescriptionLanguageFileType Svg
```


An SVG file is a Scalar Vector Graphics file that uses XML based text format for describing the appearance of an image. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/svg

### Eps {#Eps}
```
public static final PageDescriptionLanguageFileType Eps
```


Files with EPS extension essentially describe an Encapsulated PostScript language program that describes the appearance of a single page. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/eps

### Cgm {#Cgm}
```
public static final PageDescriptionLanguageFileType Cgm
```


Computer Graphics Metafile (CGM) is free, platform-independent, international standard metafile format for storing and exchanging of vector graphics (2D), raster graphics, and text. CGM uses object-oriented approach and many function provisions for image production. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/cgm

### Xps {#Xps}
```
public static final PageDescriptionLanguageFileType Xps
```


An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. This format was developed by Microsoft as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/xps

### Tex {#Tex}
```
public static final PageDescriptionLanguageFileType Tex
```


TeX is a language that comprises of programming as well as mark-up features, used to typeset documents. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/tex

### Ps {#Ps}
```
public static final PageDescriptionLanguageFileType Ps
```


PostScript (PS) is a general-purpose page description language used in the business of desktop and electronic publishing. The main focus of PostScript (PS) is to facilitate the two-dimensional graphic design. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/ps

### Pcl {#Pcl}
```
public static final PageDescriptionLanguageFileType Pcl
```


PCL stands for Printer Command Language which is a Page Description Language introduced by Hewlett Packard (HP). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/pcl

### Oxps {#Oxps}
```
public static final PageDescriptionLanguageFileType Oxps
```


The file format OXPS is known as Open XML Paper Specification. It\\u2019s a page description language and document format. Microsoft is the developer of this format. OXPS file format is very much familiar to these PDF files. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/page-description-language/oxps

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
