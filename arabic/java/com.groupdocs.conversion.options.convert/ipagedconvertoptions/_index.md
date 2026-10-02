---
title: "IPagedConvertOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يمثل خيارات التحويل التي تسمح بتحديد حدود الصفحات عن طريق تحديد الصفحة البداية وعدد الصفحات"
type: docs
weight: 55
url: /ar/java/com.groupdocs.conversion.options.convert/ipagedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPagedConvertOptions extends IConvertOptions
```

يمثل خيارات التحويل التي تسمح بتحديد حدود الصفحات عن طريق تحديد الصفحة البداية وعدد الصفحات

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | يحصل على رقم الصفحة للبدء بالتحويل منها. |
|
|  | [setPageNumber(int pageNumber)](#setPageNumber-int-) | يضبط رقم الصفحة للبدء بالتحويل منها. |
|
|  | [getPagesCount()](#getPagesCount--) | يحصل على عدد الصفحات التي سيتم تحويلها بدءًا من PageNumber. |
|
|  | [setPagesCount(int pagesCount)](#setPagesCount-int-) | يضبط عدد الصفحات التي سيتم تحويلها بدءًا من PageNumber. |
|
### getPageNumber() {#getPageNumber--}
```
public abstract Integer getPageNumber()
```


يحصل على رقم الصفحة للبدء بالتحويل منها.


**Returns:**
java.lang.Integer - رقم الصفحة التي يبدأ التحويل منها.

### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public abstract void setPageNumber(int pageNumber)
```


يضبط رقم الصفحة للبدء بالتحويل منها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pageNumber | int | رقم الصفحة التي يبدأ التحويل منها. |
|

### getPagesCount() {#getPagesCount--}
```
public abstract Integer getPagesCount()
```


يحصل على عدد الصفحات التي سيتم تحويلها بدءًا من PageNumber.


**Returns:**
java.lang.Integer - عدد الصفحات التي سيتم تحويلها بدءًا من PageNumber.

### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public abstract void setPagesCount(int pagesCount)
```


يضبط عدد الصفحات التي سيتم تحويلها بدءًا من PageNumber.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pagesCount | int | عدد الصفحات التي سيتم تحويلها بدءًا من PageNumber. |
|

