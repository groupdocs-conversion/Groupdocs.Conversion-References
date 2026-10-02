---
title: "PdfConvertOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "转换为 Pdf 文件类型的选项。"
type: docs
weight: 25
url: /zh/java/com.groupdocs.conversion.options.convert/pdfconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class PdfConvertOptions extends CommonConvertOptions<PdfFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions
```

转换为 Pdf 文件类型的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PdfConvertOptions()](#PdfConvertOptions--) | 初始化 [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions) 类的新实例。 |
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
|  | [getPdfOptions()](#getPdfOptions--) | Pdf 特定的转换选项 |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-) | Pdf 特定的转换选项 |
|
|  | [getRotate()](#getRotate--) | 页面旋转 |
|
|  | [setRotate(Rotation value)](#setRotate-com.groupdocs.conversion.options.convert.Rotation-) | 页面旋转 |
|
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
### PdfConvertOptions() {#PdfConvertOptions--}
```
public PdfConvertOptions()
```


初始化 [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions) 类的新实例。


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

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Pdf 特定的转换选项


**Returns:**
[PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Pdf 特定的转换选项


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions) |  |

### getRotate() {#getRotate--}
```
public final Rotation getRotate()
```


页面旋转


**Returns:**
[Rotation](../../com.groupdocs.conversion.options.convert/rotation)
### setRotate(Rotation value) {#setRotate-com.groupdocs.conversion.options.convert.Rotation-}
```
public final void setRotate(Rotation value)
```


页面旋转


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rotation](../../com.groupdocs.conversion.options.convert/rotation) |  |

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

