---
title: "PdfFormattingOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义 Pdf 格式化选项。"
type: docs
weight: 28
url: /zh/java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

定义 Pdf 格式化选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getCenterWindow()](#getCenterWindow--) | 指定文档窗口的位置是否会居中显示在屏幕上。 |
|
|  | [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | 指定文档窗口的位置是否会居中显示在屏幕上。 |
|
|  | [getDirection()](#getDirection--) | 设置文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。 |
|
|  | [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | 设置文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。 |
|
|  | [getDisplayDocTitle()](#getDisplayDocTitle--) | 指定文档窗口的标题栏是否应显示文档标题。 |
|
|  | [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | 指定文档窗口的标题栏是否应显示文档标题。 |
|
|  | [getFitWindow()](#getFitWindow--) | 指定文档窗口是否必须调整大小以适应首次显示的页面。 |
|
|  | [setFitWindow(boolean value)](#setFitWindow-boolean-) | 指定文档窗口是否必须调整大小以适应首次显示的页面。 |
|
|  | [getHideMenuBar()](#getHideMenuBar--) | 指定文档处于活动状态时是否应隐藏菜单栏。 |
|
|  | [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | 指定文档处于活动状态时是否应隐藏菜单栏。 |
|
|  | [getHideToolBar()](#getHideToolBar--) | 指定文档处于活动状态时是否应隐藏工具栏。 |
|
|  | [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | 指定文档处于活动状态时是否应隐藏工具栏。 |
|
|  | [getHideWindowUI()](#getHideWindowUI--) | 指定文档处于活动状态时是否应隐藏用户界面元素。 |
|
|  | [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | 指定文档处于活动状态时是否应隐藏用户界面元素。 |
|
|  | [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | 设置页面模式，指定退出全屏模式时文档的显示方式。 |
|
|  | [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | 设置页面模式，指定退出全屏模式时文档的显示方式。 |
|
|  | [getPageLayout()](#getPageLayout--) | 设置打开文档时使用的页面布局。 |
|
|  | [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | 设置打开文档时使用的页面布局。 |
|
|  | [getPageMode()](#getPageMode--) | 设置页面模式，指定打开文档时的显示方式。 |
|
|  | [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | 设置页面模式，指定打开文档时的显示方式。 |
|
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


指定文档窗口的位置是否会居中显示在屏幕上。默认值：false。


**Returns:**
布尔
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


指定文档窗口的位置是否会居中显示在屏幕上。默认值：false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


设置文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。默认值：L2R。


**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


设置文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。默认值：L2R。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


指定文档窗口的标题栏是否应显示文档标题。默认值：false。


**Returns:**
布尔
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


指定文档窗口的标题栏是否应显示文档标题。默认值：false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


指定文档窗口是否必须调整大小以适应首次显示的页面。默认值：false。


**Returns:**
布尔
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


指定文档窗口是否必须调整大小以适应首次显示的页面。默认值：false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


指定文档处于活动状态时是否应隐藏菜单栏。默认值：false。


**Returns:**
布尔
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


指定文档处于活动状态时是否应隐藏菜单栏。默认值：false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


指定文档处于活动状态时是否应隐藏工具栏。默认值：false。


**Returns:**
布尔
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


指定文档处于活动状态时是否应隐藏工具栏。默认值：false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


指定文档处于活动状态时是否应隐藏用户界面元素。默认值：false。


**Returns:**
布尔
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


指定文档处于活动状态时是否应隐藏用户界面元素。默认值：false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


设置页面模式，指定退出全屏模式时文档的显示方式。


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


设置页面模式，指定退出全屏模式时文档的显示方式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


设置打开文档时使用的页面布局。


**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


设置打开文档时使用的页面布局。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


设置页面模式，指定打开文档时的显示方式。


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


设置页面模式，指定打开文档时的显示方式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

