---
title: "ImageLoadOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "加载图像文档的选项。"
type: docs
weight: 21
url: /zh/java/com.groupdocs.conversion.options.load/imageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageLoadOptions extends LoadOptions implements Serializable
```

加载图像文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [ImageLoadOptions()](#ImageLoadOptions--) | 初始化 [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Psd、Emf、Wmf 文档类型的默认字体。 |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Psd、Emf、Wmf 文档类型的默认字体。 |
|
| [isRecognitionEnabled()](#isRecognitionEnabled--) |  |
| [getOcrConnector()](#getOcrConnector--) |  |
|  | [setOcrConnector(IOcrConnector ocrConnector)](#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-) | 设置图像 OCR 连接器 |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | 在加载文档之前重置字体文件夹 |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### ImageLoadOptions() {#ImageLoadOptions--}
```
public ImageLoadOptions()
```


初始化 [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions) 类的新实例。


### getFormat() {#getFormat--}
```
public final ImageFileType getFormat()
```


输入文档文件类型


**Returns:**
[ImageFileType](../../com.groupdocs.conversion.filetypes/imagefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Psd、Emf、Wmf 文档类型的默认字体。如果缺少字体，将使用以下字体。


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Psd、Emf、Wmf 文档类型的默认字体。如果缺少字体，将使用以下字体。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### isRecognitionEnabled() {#isRecognitionEnabled--}
```
public boolean isRecognitionEnabled()
```




**Returns:**
布尔
### getOcrConnector() {#getOcrConnector--}
```
public IOcrConnector getOcrConnector()
```




**Returns:**
[IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector)
### setOcrConnector(IOcrConnector ocrConnector) {#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-}
```
public void setOcrConnector(IOcrConnector ocrConnector)
```


设置图像 OCR 连接器


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | ocrConnector | [IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector) | OCR 连接器实例 |
|

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


在加载文档之前重置字体文件夹


**Returns:**
布尔
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resetFontFolders | 布尔 |  |

