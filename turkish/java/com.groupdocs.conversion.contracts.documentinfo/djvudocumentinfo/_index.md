---
title: "DjVuDocumentInfo"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "DjVu belge üst verilerini içerir"
type: docs
weight: 15
url: /tr/java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo), [com.groupdocs.conversion.contracts.documentinfo.ImageDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/imagedocumentinfo)
```
public class DjVuDocumentInfo extends ImageDocumentInfo
```

DjVu belge üst verilerini içerir

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DjVuDocumentInfo(DjvuImage image, FileType format, long size)](#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getVerticalResolution()](#getVerticalResolution--) | Dikey çözünürlüğü alır |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Yatay çözünürlüğü al |
|
|  | [getOpacity()](#getOpacity--) | Görüntü opaklığını alır |
|
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Dikey çözünürlüğü alır


**Returns:**
double - dikey çözünürlük

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Yatay çözünürlüğü al


**Returns:**
double - yatay çözünürlük

### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Görüntü opaklığını alır


**Returns:**
float - görüntü opaklığı

