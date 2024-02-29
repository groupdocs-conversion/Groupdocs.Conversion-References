---
title: DjVuDocumentInfo
second_title: GroupDocs.Conversion for Java API Reference
description: Contains DjVu document metadata
type: docs
weight: 15
url: /java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo), [com.groupdocs.conversion.contracts.documentinfo.ImageDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/imagedocumentinfo)
```
public class DjVuDocumentInfo extends ImageDocumentInfo
```

Contains DjVu document metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [DjVuDocumentInfo(DjvuImage image, FileType format, long size)](#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getVerticalResolution()](#getVerticalResolution--) | Gets vertical resolution |
| [getHorizontalResolution()](#getHorizontalResolution--) | Get horizontal resolution |
| [getOpacity()](#getOpacity--) | Gets image opacity |
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Gets vertical resolution

**Returns:**
double - vertical resolution
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Get horizontal resolution

**Returns:**
double - horizontal resolution
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Gets image opacity

**Returns:**
float - image opacity
