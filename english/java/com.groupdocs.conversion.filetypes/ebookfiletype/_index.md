---
title: EBookFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines CAD documents Computer Aided Design that are used for a 3D graphics file formats and may contain 2D or 3D designs.
type: docs
weight: 14
url: /java/com.groupdocs.conversion.filetypes/ebookfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EBookFileType extends FileType implements Serializable
```

Defines CAD documents (Computer Aided Design) that are used for a 3D graphics file formats and may contain 2D or 3D designs. Includes the following types: [Epub](../../com.groupdocs.conversion.filetypes/ebookfiletype\#Epub), [Mobi](../../com.groupdocs.conversion.filetypes/ebookfiletype\#Mobi), [Azw3](../../com.groupdocs.conversion.filetypes/ebookfiletype\#Azw3), Learn more about CAD formats [here][].


[here]: https://wiki.fileformat.com/cad
## Constructors

| Constructor | Description |
| --- | --- |
| [EBookFileType()](#EBookFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [Epub](#Epub) | EPUB extension are an e-book file format that provide a standard digital publication format for publishers and consumers. |
| [Mobi](#Mobi) | The MOBI file format is one of the most widely used ebook file format. |
| [Azw3](#Azw3) | AZW3, also known as Kindle Format 8 (KF8), is the modified version of the AZW ebook digital file format developed for Amazon Kindle devices. |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### EBookFileType() {#EBookFileType--}
```
public EBookFileType()
```


Serialization constructor

### Epub {#Epub}
```
public static final EBookFileType Epub
```


EPUB extension are an e-book file format that provide a standard digital publication format for publishers and consumers. The format has been so common by now that it is supported by many e-readers and software applications. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/ebook/epub

### Mobi {#Mobi}
```
public static final EBookFileType Mobi
```


The MOBI file format is one of the most widely used ebook file format. The format is an enhancement to the old OEB (Open Ebook Format) format and was used as proprietary format for Mobipocket Reader. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/ebook/mobi

### Azw3 {#Azw3}
```
public static final EBookFileType Azw3
```


AZW3, also known as Kindle Format 8 (KF8), is the modified version of the AZW ebook digital file format developed for Amazon Kindle devices. The format is an enhancement to older AZW files and is used on Kindle Fire devices only with backward compatibility for the ancestor file format i.e. MOBI and AZW. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/ebook/azw3/

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
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
