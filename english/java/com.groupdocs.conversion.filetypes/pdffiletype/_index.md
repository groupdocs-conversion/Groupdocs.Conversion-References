---
title: PdfFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines Pdf documents.
type: docs
weight: 18
url: /java/com.groupdocs.conversion.filetypes/pdffiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFileType extends FileType implements Serializable
```

Defines Pdf documents. Includes the following file types: [PdfFileType\#Epub](../../com.groupdocs.conversion.filetypes/pdffiletype\#Epub), [PdfFileType\#Pdf](../../com.groupdocs.conversion.filetypes/pdffiletype\#Pdf), [PdfFileType\#Xps](../../com.groupdocs.conversion.filetypes/pdffiletype\#Xps).
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileType()](#PdfFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [Pdf](#Pdf) | Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. |
| [Epub](#Epub) | EPUB extension are an e-book file format that provide a standard digital publication format for publishers and consumers. |
| [Xps](#Xps) | An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. |
| [Tex](#Tex) | TeX is a language that comprises of programming as well as mark-up features, used to typeset documents. |
| [Ps](#Ps) | PostScript (PS) is a general-purpose page description language used in the business of desktop and electronic publishing. |
| [Pcl](#Pcl) | PCL stands for Printer Command Language which is a Page Description Language introduced by Hewlett Packard (HP). |
| [Oxps](#Oxps) | Oxps document format |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PdfFileType() {#PdfFileType--}
```
public PdfFileType()
```


Serialization constructor

### Pdf {#Pdf}
```
public static final PdfFileType Pdf
```


Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. The purpose of this file format was to introduce a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/view/pdf

### Epub {#Epub}
```
public static final PdfFileType Epub
```


EPUB extension are an e-book file format that provide a standard digital publication format for publishers and consumers. The format has been so common by now that it is supported by many e-readers and software applications. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/ebook/epub

### Xps {#Xps}
```
public static final PdfFileType Xps
```


An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. This format was developed by Microsoft as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/xps

### Tex {#Tex}
```
public static final PdfFileType Tex
```


TeX is a language that comprises of programming as well as mark-up features, used to typeset documents. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/tex

### Ps {#Ps}
```
public static final PdfFileType Ps
```


PostScript (PS) is a general-purpose page description language used in the business of desktop and electronic publishing. The main focus of PostScript (PS) is to facilitate the two-dimensional graphic design. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/ps

### Pcl {#Pcl}
```
public static final PdfFileType Pcl
```


PCL stands for Printer Command Language which is a Page Description Language introduced by Hewlett Packard (HP). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/pcl

### Oxps {#Oxps}
```
public static final PdfFileType Oxps
```


Oxps document format

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
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
