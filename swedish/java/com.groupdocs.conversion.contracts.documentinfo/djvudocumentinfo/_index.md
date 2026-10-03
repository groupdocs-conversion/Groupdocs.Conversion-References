---
title: "DjVuDocumentInfo"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Innehåller metadata för DjVu‑dokument"
type: docs
weight: 15
url: /sv/java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo), [com.groupdocs.conversion.contracts.documentinfo.ImageDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/imagedocumentinfo)
```
public class DjVuDocumentInfo extends ImageDocumentInfo
```

Innehåller metadata för DjVu‑dokument

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DjVuDocumentInfo(DjvuImage image, FileType format, long size)](#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getVerticalResolution()](#getVerticalResolution--) | Hämtar vertikal upplösning |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Hämta horisontell upplösning |
|
|  | [getOpacity()](#getOpacity--) | Hämtar bildens opacitet |
|
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| storlek | long |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Hämtar vertikal upplösning


**Returns:**
double - vertikal upplösning

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Hämta horisontell upplösning


**Returns:**
double - horisontell upplösning

### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Hämtar bildens opacitet


**Returns:**
float - bildens opacitet

