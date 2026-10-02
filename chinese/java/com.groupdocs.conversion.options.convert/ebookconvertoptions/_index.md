---
title: "EBookConvertOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "转换为 EBook 文件类型的选项。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.conversion.options.convert/ebookconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class EBookConvertOptions extends CommonConvertOptions<EBookFileType> implements IPageSizeConvertOptions, IPageOrientationConvertOptions
```

转换为 EBook 文件类型的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [EBookConvertOptions()](#EBookConvertOptions--) | 初始化类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
### EBookConvertOptions() {#EBookConvertOptions--}
```
public EBookConvertOptions()
```


初始化类的新实例。


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

