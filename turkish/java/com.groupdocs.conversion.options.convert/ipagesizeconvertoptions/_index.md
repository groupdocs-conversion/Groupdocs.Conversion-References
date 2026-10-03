---
title: "IPageSizeConvertOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Sayfa boyutunu destekleyen dönüştürme seçeneklerini temsil eder"
type: docs
weight: 54
url: /tr/java/com.groupdocs.conversion.options.convert/ipagesizeconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageSizeConvertOptions extends IConvertOptions
```

Sayfa boyutunu destekleyen dönüştürme seçeneklerini temsil eder

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Dönüştürmeden sonra istenen sayfa boyutunu alır |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) | Dönüştürmeden sonra istenen sayfa boyutunu ayarlar |
|
|  | [getPageWidth()](#getPageWidth--) | PageSize.Custom olarak ayarlanmışsa belirtilen sayfa genişliği puan cinsinden |
|
|  | [setPageWidth(float pageWidth)](#setPageWidth-float-) | İstenen sayfa genişliğini ayarla |
|
|  | [getPageHeight()](#getPageHeight--) | PageSize.Custom olarak ayarlanmışsa belirtilen sayfa yüksekliği puan cinsinden |
|
|  | [setPageHeight(float pageHeight)](#setPageHeight-float-) | İstenen sayfa yüksekliğini ayarla |
|
### getPageSize() {#getPageSize--}
```
public abstract PageSize getPageSize()
```


Dönüştürmeden sonra istenen sayfa boyutunu alır


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public abstract void setPageSize(PageSize pageSize)
```


Dönüştürmeden sonra istenen sayfa boyutunu ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


PageSize.Custom olarak ayarlanmışsa belirtilen sayfa genişliği puan cinsinden


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public abstract void setPageWidth(float pageWidth)
```


İstenen sayfa genişliğini ayarla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


PageSize.Custom olarak ayarlanmışsa belirtilen sayfa yüksekliği puan cinsinden


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public abstract void setPageHeight(float pageHeight)
```


İstenen sayfa yüksekliğini ayarla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageHeight | float |  |

