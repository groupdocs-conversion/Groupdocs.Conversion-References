---
title: "DjVuDocumentInfo"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Bevat metadata van DjVu-document"
type: docs
weight: 15
url: /nl/java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo), [com.groupdocs.conversion.contracts.documentinfo.ImageDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/imagedocumentinfo)
```
public class DjVuDocumentInfo extends ImageDocumentInfo
```

Bevat metadata van DjVu-document

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [DjVuDocumentInfo(DjvuImage image, FileType format, long size)](#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getVerticalResolution()](#getVerticalResolution--) | Haalt verticale resolutie op |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Haalt horizontale resolutie op |
|
|  | [getOpacity()](#getOpacity--) | Haalt beeldtransparantie op |
|
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| afbeelding | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Haalt verticale resolutie op


**Returns:**
double - verticale resolutie

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Haalt horizontale resolutie op


**Returns:**
double - horizontale resolutie

### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Haalt beeldtransparantie op


**Returns:**
float - beeldtransparantie

