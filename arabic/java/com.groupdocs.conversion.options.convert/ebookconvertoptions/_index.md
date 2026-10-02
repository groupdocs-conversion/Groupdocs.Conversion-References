---
title: "EBookConvertOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات التحويل إلى نوع ملف EBook."
type: docs
weight: 14
url: /ar/java/com.groupdocs.conversion.options.convert/ebookconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class EBookConvertOptions extends CommonConvertOptions<EBookFileType> implements IPageSizeConvertOptions, IPageOrientationConvertOptions
```

خيارات التحويل إلى نوع ملف EBook.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [EBookConvertOptions()](#EBookConvertOptions--) | يقوم بإنشاء مثيل جديد للفئة. |
|
## الطرق

| طريقة | الوصف |
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


يقوم بإنشاء مثيل جديد للفئة.


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


يسترجع حجم الصفحة المطلوب بعد التحويل


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


يضبط حجم الصفحة المطلوب بعد التحويل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


عرض الصفحة المحدد بالنقاط إذا تم تعيينه إلى PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


يضبط عرض الصفحة المطلوب


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


ارتفاع الصفحة المحدد بالنقاط إذا تم تعيينه إلى PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


يضبط ارتفاع الصفحة المطلوب


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageHeight | float |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


يسترجع اتجاه الصفحة بعد التحويل


**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


يضبط اتجاه الصفحة المطلوب بعد التحويل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

