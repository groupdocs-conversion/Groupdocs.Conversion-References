---
title: "DjVuDocumentInfo"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Enthält Metadaten für DjVu-Dokumente"
type: docs
weight: 15
url: /de/java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo), [com.groupdocs.conversion.contracts.documentinfo.ImageDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/imagedocumentinfo)
```
public class DjVuDocumentInfo extends ImageDocumentInfo
```

Enthält Metadaten für DjVu-Dokumente

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DjVuDocumentInfo(DjvuImage image, FileType format, long size)](#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getVerticalResolution()](#getVerticalResolution--) | Ermittelt vertikale Auflösung |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Horizontale Auflösung abrufen |
|
|  | [getOpacity()](#getOpacity--) | Ermittelt Bild-Transparenz |
|
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bild | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| Größe | long |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Ermittelt vertikale Auflösung


**Returns:**
double - vertikale Auflösung

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Horizontale Auflösung abrufen


**Returns:**
double - horizontale Auflösung

### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Ermittelt Bild-Transparenz


**Returns:**
float - Bildtransparenz

