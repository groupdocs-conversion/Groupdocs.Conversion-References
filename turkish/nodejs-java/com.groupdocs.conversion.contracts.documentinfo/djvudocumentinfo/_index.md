---
title: "DjVuDocumentInfo"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "DjVu belge üst verilerini içerir"
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
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
| [getVerticalResolution()](#getVerticalResolution--) | Dikey çözünürlüğü alır |
| [getHorizontalResolution()](#getHorizontalResolution--) | Yatay çözünürlüğü alır |
| [getOpacity()](#getOpacity--) | Görüntü opaklığını alır |
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
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


Yatay çözünürlüğü alır

**Returns:**
double - yatay çözünürlük
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Görüntü opaklığını alır

**Returns:**
float - görüntü opaklığı
