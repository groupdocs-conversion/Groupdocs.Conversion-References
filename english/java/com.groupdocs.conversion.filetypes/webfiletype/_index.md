---
title: WebFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines Web documents.
type: docs
weight: 27
url: /java/com.groupdocs.conversion.filetypes/webfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WebFileType extends FileType implements Serializable
```

Defines Web documents. Includes the following types: [Xml](../../com.groupdocs.conversion.filetypes/webfiletype\#Xml), [Json](../../com.groupdocs.conversion.filetypes/webfiletype\#Json), [Html](../../com.groupdocs.conversion.filetypes/webfiletype\#Html), [Htm](../../com.groupdocs.conversion.filetypes/webfiletype\#Htm), [Mht](../../com.groupdocs.conversion.filetypes/webfiletype\#Mht), [Mhtml](../../com.groupdocs.conversion.filetypes/webfiletype\#Mhtml), [Chm](../../com.groupdocs.conversion.filetypes/webfiletype\#Chm), Learn more about web formats [here][].


[here]: https://wiki.fileformat.com/web
## Constructors

| Constructor | Description |
| --- | --- |
| [WebFileType()](#WebFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [Xml](#Xml) | XML stands for Extensible Markup Language that is similar to HTML but different in using tags for defining objects. |
| [Json](#Json) | JSON (JavaScript Object Notation) is an open standard file format for sharing data that uses human-readable text to store and transmit data. |
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
| [webFileType(DataFileType d)](#webFileType-com.groupdocs.conversion.filetypes.DataFileType-) | Convert DataFileType to WebFileType explicitly |
### WebFileType() {#WebFileType--}
```
public WebFileType()
```


Serialization constructor

### Xml {#Xml}
```
public static final WebFileType Xml
```


XML stands for Extensible Markup Language that is similar to HTML but different in using tags for defining objects. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/xml

### Json {#Json}
```
public static final WebFileType Json
```


JSON (JavaScript Object Notation) is an open standard file format for sharing data that uses human-readable text to store and transmit data. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/web/json

### Html {#Html}
```
public static final WebFileType Html
```


HTML (Hyper Text Markup Language) is the extension for web pages created for display in browsers. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/html

### Htm {#Htm}
```
public static final WebFileType Htm
```


HTM (Hyper Text Markup Language) is the extension for web pages created for display in browsers. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/html

### Mht {#Mht}
```
public static final WebFileType Mht
```


Files with MHTML extension represent a web page archive format that can be created by a number of different applications. The format is known as archive format because it saves the web HTML code and associated resources in a single file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### Mhtml {#Mhtml}
```
public static final WebFileType Mhtml
```


Files with MHTML extension represent a web page archive format that can be created by a number of different applications. The format is known as archive format because it saves the web HTML code and associated resources in a single file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### Chm {#Chm}
```
public static final WebFileType Chm
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
### webFileType(DataFileType d) {#webFileType-com.groupdocs.conversion.filetypes.DataFileType-}
```
public static WebFileType webFileType(DataFileType d)
```


Convert DataFileType to WebFileType explicitly

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| d | [DataFileType](../../com.groupdocs.conversion.filetypes/datafiletype) | Data file type |

**Returns:**
[WebFileType](../../com.groupdocs.conversion.filetypes/webfiletype)
