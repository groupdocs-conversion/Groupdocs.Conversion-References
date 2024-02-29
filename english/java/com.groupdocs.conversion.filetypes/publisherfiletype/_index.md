---
title: PublisherFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines Publisher documents.
type: docs
weight: 24
url: /java/com.groupdocs.conversion.filetypes/publisherfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PublisherFileType extends FileType implements Serializable
```

Defines Publisher documents. Includes the following types: [Pub](../../com.groupdocs.conversion.filetypes/publisherfiletype\#Pub), Learn more about Font formats [here][].


[here]: https://wiki.fileformat.com/publisher
## Constructors

| Constructor | Description |
| --- | --- |
| [PublisherFileType()](#PublisherFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [Pub](#Pub) | A PUB file is a Microsoft Publisher document file format. |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PublisherFileType() {#PublisherFileType--}
```
public PublisherFileType()
```


Serialization constructor

### Pub {#Pub}
```
public static final PublisherFileType Pub
```


A PUB file is a Microsoft Publisher document file format. It is used to create several types of design layout documents such as newsletters, flyers, brochures, postcards, etc. PUB files can contain text, raster and vector images. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/publisher/pub/

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Prepared default load options for the source file type

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
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
