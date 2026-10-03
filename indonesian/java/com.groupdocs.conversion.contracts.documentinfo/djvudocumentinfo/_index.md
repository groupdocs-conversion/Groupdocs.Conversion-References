---
title: "DjVuDocumentInfo"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Berisi metadata dokumen DjVu"
type: docs
weight: 15
url: /id/java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo), [com.groupdocs.conversion.contracts.documentinfo.ImageDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/imagedocumentinfo)
```
public class DjVuDocumentInfo extends ImageDocumentInfo
```

Berisi metadata dokumen DjVu

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DjVuDocumentInfo(DjvuImage image, FileType format, long size)](#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getVerticalResolution()](#getVerticalResolution--) | Mendapatkan resolusi vertikal |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Dapatkan resolusi horizontal |
|
|  | [getOpacity()](#getOpacity--) | Mendapatkan opasitas gambar |
|
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Mendapatkan resolusi vertikal


**Returns:**
double - resolusi vertikal

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Dapatkan resolusi horizontal


**Returns:**
double - resolusi horizontal

### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Mendapatkan opasitas gambar


**Returns:**
float - opasitas gambar

