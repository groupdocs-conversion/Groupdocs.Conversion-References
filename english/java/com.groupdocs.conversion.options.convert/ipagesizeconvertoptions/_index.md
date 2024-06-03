---
title: IPageSizeConvertOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Represents convert options that support page size
type: docs
weight: 53
url: /java/com.groupdocs.conversion.options.convert/ipagesizeconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageSizeConvertOptions extends IConvertOptions
```

Represents convert options that support page size
## Methods

| Method | Description |
| --- | --- |
| [getPageSize()](#getPageSize--) | Gets desired page size after conversion |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) | Set desired page size after conversion |
| [getPageWidth()](#getPageWidth--) | Specified page width in points if  is set to PageSize.Custom |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) | Set desired page width |
| [getPageHeight()](#getPageHeight--) | Specified page height in points if  is set to PageSize.Custom |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) | Set desired page height |
### getPageSize() {#getPageSize--}
```
public abstract PageSize getPageSize()
```


Gets desired page size after conversion

**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public abstract void setPageSize(PageSize pageSize)
```


Set desired page size after conversion

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


Specified page width in points if  is set to PageSize.Custom

**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public abstract void setPageWidth(float pageWidth)
```


Set desired page width

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


Specified page height in points if  is set to PageSize.Custom

**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public abstract void setPageHeight(float pageHeight)
```


Set desired page height

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageHeight | float |  |

