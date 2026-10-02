---
title: "IPageSizeConvertOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يمثل خيارات التحويل التي تدعم حجم الصفحة"
type: docs
weight: 54
url: /ar/java/com.groupdocs.conversion.options.convert/ipagesizeconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageSizeConvertOptions extends IConvertOptions
```

يمثل خيارات التحويل التي تدعم حجم الصفحة

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | يسترجع حجم الصفحة المطلوب بعد التحويل |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) | يضبط حجم الصفحة المطلوب بعد التحويل |
|
|  | [getPageWidth()](#getPageWidth--) | عرض الصفحة المحدد بالنقاط إذا تم تعيينه إلى PageSize.Custom |
|
|  | [setPageWidth(float pageWidth)](#setPageWidth-float-) | يضبط عرض الصفحة المطلوب |
|
|  | [getPageHeight()](#getPageHeight--) | ارتفاع الصفحة المحدد بالنقاط إذا تم تعيينه إلى PageSize.Custom |
|
|  | [setPageHeight(float pageHeight)](#setPageHeight-float-) | يضبط ارتفاع الصفحة المطلوب |
|
### getPageSize() {#getPageSize--}
```
public abstract PageSize getPageSize()
```


يسترجع حجم الصفحة المطلوب بعد التحويل


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public abstract void setPageSize(PageSize pageSize)
```


يضبط حجم الصفحة المطلوب بعد التحويل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


عرض الصفحة المحدد بالنقاط إذا تم تعيينه إلى PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public abstract void setPageWidth(float pageWidth)
```


يضبط عرض الصفحة المطلوب


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


ارتفاع الصفحة المحدد بالنقاط إذا تم تعيينه إلى PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public abstract void setPageHeight(float pageHeight)
```


يضبط ارتفاع الصفحة المطلوب


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageHeight | float |  |

