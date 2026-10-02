---
title: "DjVuDocumentInfo"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "包含 DjVu 文档元数据"
type: docs
weight: 15
url: /zh/java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo), [com.groupdocs.conversion.contracts.documentinfo.ImageDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/imagedocumentinfo)
```
public class DjVuDocumentInfo extends ImageDocumentInfo
```

包含 DjVu 文档元数据

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DjVuDocumentInfo(DjvuImage image, FileType format, long size)](#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getVerticalResolution()](#getVerticalResolution--) | 获取垂直分辨率 |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | 获取水平分辨率 |
|
|  | [getOpacity()](#getOpacity--) | 获取图像不透明度 |
|
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 大小 | long |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


获取垂直分辨率


**Returns:**
double - 垂直分辨率

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


获取水平分辨率


**Returns:**
double - 水平分辨率

### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


获取图像不透明度


**Returns:**
float - 图像不透明度

