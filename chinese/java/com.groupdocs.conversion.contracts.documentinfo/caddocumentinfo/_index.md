---
title: "CadDocumentInfo"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "包含 CAD 文档元数据"
type: docs
weight: 11
url: /zh/java/com.groupdocs.conversion.contracts.documentinfo/caddocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class CadDocumentInfo extends DocumentInfo
```

包含 CAD 文档元数据

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CadDocumentInfo(Image cad, FileType format, long size)](#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 宽度 |
|
|  | [getHeight()](#getHeight--) | 高度 |
|
|  | [getLayouts()](#getLayouts--) | 文档中的布局 |
|
|  | [getLayers()](#getLayers--) | 文档中的图层 |
|
### CadDocumentInfo(Image cad, FileType format, long size) {#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public CadDocumentInfo(Image cad, FileType format, long size)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cad | com.aspose.cad.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 大小 | long |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


宽度


**Returns:**
int - 宽度

### getHeight() {#getHeight--}
```
public int getHeight()
```


高度


**Returns:**
int - 高度

### getLayouts() {#getLayouts--}
```
public List<String> getLayouts()
```


文档中的布局


**Returns:**
java.util.List<java.lang.String> - 文档中的布局

### getLayers() {#getLayers--}
```
public List<String> getLayers()
```


文档中的图层


**Returns:**
java.util.List<java.lang.String> - 文档中的图层

