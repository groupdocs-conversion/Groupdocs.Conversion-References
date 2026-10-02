---
title: "CadConvertOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات التحويل إلى نوع Cad."
type: docs
weight: 10
url: /ar/java/com.groupdocs.conversion.options.convert/cadconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions)
```
public class CadConvertOptions extends ConvertOptions<CadFileType> implements IPagedConvertOptions
```

خيارات التحويل إلى نوع Cad.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [CadConvertOptions()](#CadConvertOptions--) | يقوم بإنشاء مثيل جديد للفئة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
### CadConvertOptions() {#CadConvertOptions--}
```
public CadConvertOptions()
```


يقوم بإنشاء مثيل جديد للفئة.


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

