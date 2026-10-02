---
title: "DjVuDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحتوي على بيانات تعريف مستند DjVu"
type: docs
weight: 15
url: /ar/java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo), [com.groupdocs.conversion.contracts.documentinfo.ImageDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/imagedocumentinfo)
```
public class DjVuDocumentInfo extends ImageDocumentInfo
```

يحتوي على بيانات تعريف مستند DjVu

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [DjVuDocumentInfo(DjvuImage image, FileType format, long size)](#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getVerticalResolution()](#getVerticalResolution--) | يحصل على الدقة العمودية |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | احصل على الدقة الأفقية |
|
|  | [getOpacity()](#getOpacity--) | يحصل على شفافية الصورة |
|
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


يحصل على الدقة العمودية


**Returns:**
double - الدقة العمودية

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


احصل على الدقة الأفقية


**Returns:**
double - الدقة الأفقية

### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


يحصل على شفافية الصورة


**Returns:**
float - شفافية الصورة

