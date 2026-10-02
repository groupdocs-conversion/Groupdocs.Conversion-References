---
title: "WordProcessingConvertOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "用于转换为 WordProcessing 文件类型的选项。"
type: docs
weight: 48
url: /zh/java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions), [com.groupdocs.conversion.options.convert.IPdfRecognitionModeOptions](../../com.groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions)
```
public class WordProcessingConvertOptions extends CommonConvertOptions<WordProcessingFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions, IPdfRecognitionModeOptions
```

用于转换为 WordProcessing 文件类型的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | 初始化 [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getDpi()](#getDpi--) | 转换后所需的页面 DPI。 |
|
|  | [setDpi(int value)](#setDpi-int-) | 转换后所需的页面 DPI。 |
|
|  | [getPassword()](#getPassword--) | 如果您想使用密码保护转换后的文档，请设置此属性。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 如果您想使用密码保护转换后的文档，请设置此属性。 |
|
|  | [getRtfOptions()](#getRtfOptions--) | RTF 特定转换选项 |
|
|  | [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | RTF 特定转换选项 |
|
|  | [getZoom()](#getZoom--) | 指定缩放比例（百分比）。 |
|
|  | [setZoom(int value)](#setZoom-int-) | 指定缩放比例（百分比）。 |
|
|  | [getMarginTop()](#getMarginTop--) | 转换后所需的页面顶部边距（单位：点）。 |
|
|  | [setMarginTop(float value)](#setMarginTop-float-) | 转换后所需的页面顶部边距（单位：点）。 |
|
|  | [getMarginBottom()](#getMarginBottom--) | 转换后所需的页面底部边距（单位：点）。 |
|
|  | [setMarginBottom(float value)](#setMarginBottom-float-) | 转换后所需的页面底部边距（单位：点）。 |
|
|  | [getMarginLeft()](#getMarginLeft--) | 转换后所需的页面左侧边距（单位：点）。 |
|
|  | [setMarginLeft(float value)](#setMarginLeft-float-) | 转换后所需的页面左侧边距（单位：点）。 |
|
|  | [getMarginRight()](#getMarginRight--) | 转换后所需的页面右侧边距（单位：点）。 |
|
|  | [setMarginRight(float value)](#setMarginRight-float-) | 转换后所需的页面右侧边距（单位：点）。 |
|
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
| [getPdfRecognitionMode()](#getPdfRecognitionMode--) |  |
| [setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)](#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-) |  |
|  | [getMarkdownOptions()](#getMarkdownOptions--) | 获取 |
|
|  | [setMarkdownOptions(MarkdownOptions markdownOptions)](#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-) | 设置 |
|
### WordProcessingConvertOptions() {#WordProcessingConvertOptions--}
```
public WordProcessingConvertOptions()
```


初始化 [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions) 类的新实例。


### getDpi() {#getDpi--}
```
public final int getDpi()
```


转换后所需的页面 DPI。默认分辨率为：96 dpi。


**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


转换后所需的页面 DPI。默认分辨率为：96 dpi。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


如果您想使用密码保护转换后的文档，请设置此属性。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


如果您想使用密码保护转换后的文档，请设置此属性。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getRtfOptions() {#getRtfOptions--}
```
public final RtfOptions getRtfOptions()
```


RTF 特定转换选项


**Returns:**
[RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions)
### setRtfOptions(RtfOptions value) {#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-}
```
public final void setRtfOptions(RtfOptions value)
```


RTF 特定转换选项


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions) |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


指定缩放比例（百分比）。默认值为 100。
默认缩放在 Microsoft Word 2010 之前受支持。从 Microsoft Word 2013 开始，默认缩放不再设置到文档，而是似乎使用上一次打开的文档的缩放因子。


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


指定缩放比例（百分比）。默认值为 100。
默认缩放在 Microsoft Word 2010 之前受支持。从 Microsoft Word 2013 开始，默认缩放不再设置到文档，而是似乎使用上一次打开的文档的缩放因子。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getMarginTop() {#getMarginTop--}
```
public final float getMarginTop()
```


转换后所需的页面顶部边距（单位：点）。


**Returns:**
float
### setMarginTop(float value) {#setMarginTop-float-}
```
public final void setMarginTop(float value)
```


转换后所需的页面顶部边距（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getMarginBottom() {#getMarginBottom--}
```
public final float getMarginBottom()
```


转换后所需的页面底部边距（单位：点）。


**Returns:**
float
### setMarginBottom(float value) {#setMarginBottom-float-}
```
public final void setMarginBottom(float value)
```


转换后所需的页面底部边距（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


转换后所需的页面左侧边距（单位：点）。


**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


转换后所需的页面左侧边距（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


转换后所需的页面右侧边距（单位：点）。


**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


转换后所需的页面右侧边距（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


获取转换后的页面方向


**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


设置转换后所需的页面方向


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


获取转换后的目标页面大小


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


设置转换后的目标页面大小


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


如果设置为 PageSize.Custom，则指定页面宽度（单位为点）


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


设置目标页面宽度


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


如果设置为 PageSize.Custom，则指定页面高度（单位为点）


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


设置目标页面高度


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageHeight | float |  |

### getPdfRecognitionMode() {#getPdfRecognitionMode--}
```
public PdfRecognitionMode getPdfRecognitionMode()
```


获取从 pdf 转换时的识别模式


**Returns:**
[PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode)
### setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode) {#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-}
```
public void setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)
```


设置从 pdf 转换时的识别模式


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdfRecognitionMode | [PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode) |  |

### getMarkdownOptions() {#getMarkdownOptions--}
```
public MarkdownOptions getMarkdownOptions()
```


获取


**Returns:**
[MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions)
### setMarkdownOptions(MarkdownOptions markdownOptions) {#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-}
```
public void setMarkdownOptions(MarkdownOptions markdownOptions)
```


设置


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| markdownOptions | [MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions) |  |

