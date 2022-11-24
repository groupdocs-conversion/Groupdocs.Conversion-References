---
title: MarkupFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines Markup and Web file formats.
type: docs
weight: 17
url: /java/com.groupdocs.conversion.filetypes/markupfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class MarkupFileType extends FileType implements Serializable
```

Defines Markup and Web file formats. Includes the following file types: [Htm](../../com.groupdocs.conversion.filetypes/markupfiletype\#Htm), [Html](../../com.groupdocs.conversion.filetypes/markupfiletype\#Html). Learn more about Image formats [here][].


[here]: https://wiki.fileformat.com/web
## Constructors

| Constructor | Description |
| --- | --- |
| [MarkupFileType()](#MarkupFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [Html](#Html) | HTML (Hyper Text Markup Language) is the extension for web pages created for display in browsers. |
| [Htm](#Htm) | HTM (Hyper Text Markup Language) is the extension for web pages created for display in browsers. |
| [Mht](#Mht) | Files with MHTML extension represent a web page archive format that can be created by a number of different applications. |
| [Mhtml](#Mhtml) | Files with MHTML extension represent a web page archive format that can be created by a number of different applications. |
| [Chm](#Chm) | The CHM file format represents Microsoft HTML help file that consists of a collection of HTML pages. |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### MarkupFileType() {#MarkupFileType--}
```
public MarkupFileType()
```


Serialization constructor

### Html {#Html}
```
public static final MarkupFileType Html
```


HTML (Hyper Text Markup Language) is the extension for web pages created for display in browsers. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/html

### Htm {#Htm}
```
public static final MarkupFileType Htm
```


HTM (Hyper Text Markup Language) is the extension for web pages created for display in browsers. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/html

### Mht {#Mht}
```
public static final MarkupFileType Mht
```


Files with MHTML extension represent a web page archive format that can be created by a number of different applications. The format is known as archive format because it saves the web HTML code and associated resources in a single file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### Mhtml {#Mhtml}
```
public static final MarkupFileType Mhtml
```


Files with MHTML extension represent a web page archive format that can be created by a number of different applications. The format is known as archive format because it saves the web HTML code and associated resources in a single file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### Chm {#Chm}
```
public static final MarkupFileType Chm
```


The CHM file format represents Microsoft HTML help file that consists of a collection of HTML pages. It provides an index for quick accessing the topics and navigation to different parts of the help document. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/web/chm

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
