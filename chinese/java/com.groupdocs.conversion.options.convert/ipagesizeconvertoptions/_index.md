---
title: "IPageSizeConvertOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "表示支持页面尺寸的转换选项"
type: docs
weight: 54
url: /zh/java/com.groupdocs.conversion.options.convert/ipagesizeconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageSizeConvertOptions extends IConvertOptions
```

表示支持页面尺寸的转换选项

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | 获取转换后的目标页面大小 |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) | 设置转换后的目标页面大小 |
|
|  | [getPageWidth()](#getPageWidth--) | 如果设置为 PageSize.Custom，则指定页面宽度（单位为点） |
|
|  | [setPageWidth(float pageWidth)](#setPageWidth-float-) | 设置目标页面宽度 |
|
|  | [getPageHeight()](#getPageHeight--) | 如果设置为 PageSize.Custom，则指定页面高度（单位为点） |
|
|  | [setPageHeight(float pageHeight)](#setPageHeight-float-) | 设置目标页面高度 |
|
### getPageSize() {#getPageSize--}
```
public abstract PageSize getPageSize()
```


获取转换后的目标页面大小


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public abstract void setPageSize(PageSize pageSize)
```


设置转换后的目标页面大小


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


如果设置为 PageSize.Custom，则指定页面宽度（单位为点）


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public abstract void setPageWidth(float pageWidth)
```


设置目标页面宽度


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


如果设置为 PageSize.Custom，则指定页面高度（单位为点）


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public abstract void setPageHeight(float pageHeight)
```


设置目标页面高度


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageHeight | float |  |

