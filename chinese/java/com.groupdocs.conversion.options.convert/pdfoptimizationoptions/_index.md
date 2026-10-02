---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义 Pdf 优化选项。"
type: docs
weight: 29
url: /zh/java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptimizationOptions extends ValueObject implements Serializable
```

定义 Pdf 优化选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | 初始化 [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | 链接重复流 |
|
|  | [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | 链接重复流 |
|
|  | [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | 删除未使用的对象 |
|
|  | [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | 删除未使用的对象 |
|
|  | [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | 删除未使用的流 |
|
|  | [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | 删除未使用的流 |
|
|  | [getCompressImages()](#getCompressImages--) | 如果将 CompressImages 设置为 |
true
，文档中的所有图像都会重新压缩。
|
|  | [setCompressImages(boolean value)](#setCompressImages-boolean-) | 如果将 CompressImages 设置为 |
true
，文档中的所有图像都会重新压缩。
|
|  | [getImageQuality()](#getImageQuality--) | 以百分比表示的值，100% 表示质量和图像尺寸保持不变。 |
|
|  | [setImageQuality(int value)](#setImageQuality-int-) | 以百分比表示的值，100% 表示质量和图像尺寸保持不变。 |
|
|  | [getUnembedFonts()](#getUnembedFonts--) | 如果设置为 true，则使字体不嵌入 |
|
|  | [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | 如果设置为 true，则使字体不嵌入 |
|
| [getFontSubsetStrategy()](#getFontSubsetStrategy--) |  |
|  | [setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)](#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-) | 设置字体子集策略 |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


初始化 [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) 类的新实例。


### getLinkDuplicateStreams() {#getLinkDuplicateStreams--}
```
public final boolean getLinkDuplicateStreams()
```


链接重复流


**Returns:**
布尔
### setLinkDuplicateStreams(boolean value) {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```


链接重复流


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


删除未使用的对象


**Returns:**
布尔
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


删除未使用的对象


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


删除未使用的流


**Returns:**
布尔
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


删除未使用的流


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


如果将 CompressImages 设置为
true
，文档中的所有图像都会重新压缩。压缩由 ImageQuality 属性定义。


**Returns:**
布尔
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


如果将 CompressImages 设置为
true
，文档中的所有图像都会重新压缩。压缩由 ImageQuality 属性定义。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


以百分比表示的值，100% 表示质量和图像尺寸保持不变。要减小图像尺寸，请将此属性设置为小于 100 的值


**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


以百分比表示的值，100% 表示质量和图像尺寸保持不变。要减小图像尺寸，请将此属性设置为小于 100 的值


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


如果设置为 true，则使字体不嵌入


**Returns:**
布尔
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


如果设置为 true，则使字体不嵌入


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getFontSubsetStrategy() {#getFontSubsetStrategy--}
```
public PdfFontSubsetStrategy getFontSubsetStrategy()
```




**Returns:**
[PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy)
### setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy) {#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-}
```
public void setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)
```


设置字体子集策略


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontSubsetStrategy | [PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy) |  |

