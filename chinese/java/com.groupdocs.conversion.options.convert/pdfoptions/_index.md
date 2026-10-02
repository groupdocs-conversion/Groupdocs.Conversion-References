---
title: "PdfOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "转换为 Pdf 文件类型的选项。"
type: docs
weight: 30
url: /zh/java/com.groupdocs.conversion.options.convert/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptions extends ValueObject implements Serializable
```

转换为 Pdf 文件类型的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | ctor |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPdfFormat()](#getPdfFormat--) | 设置已转换文档的 pdf 格式。 |
|
|  | [setPdfFormat(PdfFormats value)](#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-) | 设置已转换文档的 pdf 格式。 |
|
|  | [getRemovePdfACompliance()](#getRemovePdfACompliance--) | 移除 Pdf-A 合规性 |
|
|  | [setRemovePdfACompliance(boolean value)](#setRemovePdfACompliance-boolean-) | 移除 Pdf-A 合规性 |
|
|  | [getZoom()](#getZoom--) | 指定缩放比例（百分比）。 |
|
|  | [setZoom(int value)](#setZoom-int-) | 指定缩放比例（百分比）。 |
|
|  | [getLinearize()](#getLinearize--) | 为 Web 线性化 PDF 文档 |
|
|  | [setLinearize(boolean value)](#setLinearize-boolean-) | 为 Web 线性化 PDF 文档 |
|
|  | [getOptimizationOptions()](#getOptimizationOptions--) | Pdf 优化选项 |
|
|  | [setOptimizationOptions(PdfOptimizationOptions value)](#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-) | Pdf 优化选项 |
|
|  | [getGrayscale()](#getGrayscale--) | 将 PDF 从 RGB 颜色空间转换为灰度 |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | 将 PDF 从 RGB 颜色空间转换为灰度 |
|
|  | [getFormattingOptions()](#getFormattingOptions--) | Pdf 格式化选项 |
|
|  | [setFormattingOptions(PdfFormattingOptions value)](#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-) | Pdf 格式化选项 |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | PDF 文档的元信息。 |
|
| [setDocumentInfo(PdfDocumentInfo documentInfo)](#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-) |  |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


ctor


### getPdfFormat() {#getPdfFormat--}
```
public final PdfFormats getPdfFormat()
```


设置已转换文档的 pdf 格式。


**Returns:**
[PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats)
### setPdfFormat(PdfFormats value) {#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-}
```
public final void setPdfFormat(PdfFormats value)
```


设置已转换文档的 pdf 格式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats) |  |

### getRemovePdfACompliance() {#getRemovePdfACompliance--}
```
public final boolean getRemovePdfACompliance()
```


移除 Pdf-A 合规性


**Returns:**
布尔
### setRemovePdfACompliance(boolean value) {#setRemovePdfACompliance-boolean-}
```
public final void setRemovePdfACompliance(boolean value)
```


移除 Pdf-A 合规性


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


指定缩放比例（百分比）。默认值为 100。


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


指定缩放比例（百分比）。默认值为 100。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLinearize() {#getLinearize--}
```
public final boolean getLinearize()
```


为 Web 线性化 PDF 文档


**Returns:**
布尔
### setLinearize(boolean value) {#setLinearize-boolean-}
```
public final void setLinearize(boolean value)
```


为 Web 线性化 PDF 文档


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getOptimizationOptions() {#getOptimizationOptions--}
```
public final PdfOptimizationOptions getOptimizationOptions()
```


Pdf 优化选项


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions)
### setOptimizationOptions(PdfOptimizationOptions value) {#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-}
```
public final void setOptimizationOptions(PdfOptimizationOptions value)
```


Pdf 优化选项


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


将 PDF 从 RGB 颜色空间转换为灰度


**Returns:**
布尔
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


将 PDF 从 RGB 颜色空间转换为灰度


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public final PdfFormattingOptions getFormattingOptions()
```


Pdf 格式化选项


**Returns:**
[PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions)
### setFormattingOptions(PdfFormattingOptions value) {#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-}
```
public final void setFormattingOptions(PdfFormattingOptions value)
```


Pdf 格式化选项


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public PdfDocumentInfo getDocumentInfo()
```


PDF 文档的元信息。


**Returns:**
[PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo)
### setDocumentInfo(PdfDocumentInfo documentInfo) {#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-}
```
public void setDocumentInfo(PdfDocumentInfo documentInfo)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| documentInfo | [PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo) |  |

