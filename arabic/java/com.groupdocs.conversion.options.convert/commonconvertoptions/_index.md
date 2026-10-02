---
title: "CommonConvertOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "فئة خيارات التحويل العامة المجردة."
type: docs
weight: 11
url: /ar/java/com.groupdocs.conversion.options.convert/commonconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IWatermarkedConvertOptions](../../com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions), [com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions), [com.groupdocs.conversion.options.convert.IPageRangedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagerangedconvertoptions)
```
public abstract class CommonConvertOptions<TFileType> extends ConvertOptions<TFileType> implements IWatermarkedConvertOptions, IPagedConvertOptions, IPageRangedConvertOptions
```

فئة خيارات التحويل العامة المجردة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getWatermark()](#getWatermark--) |  |
| [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) |  |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
| [getPages()](#getPages--) |  |
| [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) |  |
### getWatermark() {#getWatermark--}
```
public WatermarkOptions getWatermark()
```


يحصل على خيارات العلامة المائية المحددة


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public void setWatermark(WatermarkOptions watermark)
```


يضبط خيارات العلامة المائية المحددة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


يحصل على رقم الصفحة للبدء بالتحويل منها.


**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


يضبط رقم الصفحة للبدء بالتحويل منها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


يحصل على عدد الصفحات التي سيتم تحويلها بدءًا من PageNumber.


**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


يضبط عدد الصفحات التي سيتم تحويلها بدءًا من PageNumber.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pagesCount | int |  |

### getPages() {#getPages--}
```
public List<Integer> getPages()
```


يحصل على قائمة فهارس الصفحات التي سيتم تحويلها. يجب تحديدها لتحويل صفحات محددة.


**Returns:**
java.util.List<java.lang.Integer>
### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public void setPages(List<Integer> pages)
```


يضبط قائمة فهارس الصفحات التي سيتم تحويلها. يجب تحديدها لتحويل صفحات محددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pages | java.util.List<java.lang.Integer> |  |

