---
title: "IPagedConvertOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Başlangıç sayfasını ve sayfa sayısını belirterek sayfa sınırlaması yapmaya izin veren dönüştürme seçeneklerini temsil eder"
type: docs
weight: 55
url: /tr/java/com.groupdocs.conversion.options.convert/ipagedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPagedConvertOptions extends IConvertOptions
```

Başlangıç sayfasını ve sayfa sayısını belirterek sayfa sınırlaması yapmaya izin veren dönüştürme seçeneklerini temsil eder

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Dönüştürmeye başlanacak sayfa numarasını alır. |
|
|  | [setPageNumber(int pageNumber)](#setPageNumber-int-) | Dönüştürmeye başlanacak sayfa numarasını ayarlar. |
|
|  | [getPagesCount()](#getPagesCount--) | PageNumber'dan başlayarak dönüştürülecek sayfa sayısını alır. |
|
|  | [setPagesCount(int pagesCount)](#setPagesCount-int-) | PageNumber'dan başlayarak dönüştürülecek sayfa sayısını ayarlar. |
|
### getPageNumber() {#getPageNumber--}
```
public abstract Integer getPageNumber()
```


Dönüştürmeye başlanacak sayfa numarasını alır.


**Returns:**
java.lang.Integer - Dönüştürmeye başlanacak sayfa numarası.

### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public abstract void setPageNumber(int pageNumber)
```


Dönüştürmeye başlanacak sayfa numarasını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageNumber | int | Dönüştürmeye başlanacak sayfa numarası. |
|

### getPagesCount() {#getPagesCount--}
```
public abstract Integer getPagesCount()
```


PageNumber'dan başlayarak dönüştürülecek sayfa sayısını alır.


**Returns:**
java.lang.Integer - PageNumber değerinden başlayarak dönüştürülecek sayfa sayısı.

### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public abstract void setPagesCount(int pagesCount)
```


PageNumber'dan başlayarak dönüştürülecek sayfa sayısını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pagesCount | int | PageNumber değerinden başlayarak dönüştürülecek sayfa sayısı. |
|

