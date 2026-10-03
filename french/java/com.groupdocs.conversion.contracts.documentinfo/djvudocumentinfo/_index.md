---
title: "DjVuDocumentInfo"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Contient les métadonnées du document DjVu"
type: docs
weight: 15
url: /fr/java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo), [com.groupdocs.conversion.contracts.documentinfo.ImageDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/imagedocumentinfo)
```
public class DjVuDocumentInfo extends ImageDocumentInfo
```

Contient les métadonnées du document DjVu

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DjVuDocumentInfo(DjvuImage image, FileType format, long size)](#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getVerticalResolution()](#getVerticalResolution--) | Obtient la résolution verticale |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Obtenir la résolution horizontale |
|
|  | [getOpacity()](#getOpacity--) | Obtient l'opacité de l'image |
|
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Obtient la résolution verticale


**Returns:**
double - résolution verticale

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Obtenir la résolution horizontale


**Returns:**
double - résolution horizontale

### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Obtient l'opacité de l'image


**Returns:**
float - opacité de l'image

