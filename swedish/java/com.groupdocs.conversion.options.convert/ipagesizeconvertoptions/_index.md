---
title: "IPageSizeConvertOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Representerar konverteringsalternativ som stödjer sidstorlek"
type: docs
weight: 54
url: /sv/java/com.groupdocs.conversion.options.convert/ipagesizeconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageSizeConvertOptions extends IConvertOptions
```

Representerar konverteringsalternativ som stödjer sidstorlek

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Hämtar önskad sidstorlek efter konvertering |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) | Ställ in önskad sidstorlek efter konvertering |
|
|  | [getPageWidth()](#getPageWidth--) | Angiven sidbredd i punkter om den är satt till PageSize.Custom |
|
|  | [setPageWidth(float pageWidth)](#setPageWidth-float-) | Ställ in önskad sidbredd |
|
|  | [getPageHeight()](#getPageHeight--) | Angiven sidhöjd i punkter om den är satt till PageSize.Custom |
|
|  | [setPageHeight(float pageHeight)](#setPageHeight-float-) | Ställ in önskad sidhöjd |
|
### getPageSize() {#getPageSize--}
```
public abstract PageSize getPageSize()
```


Hämtar önskad sidstorlek efter konvertering


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public abstract void setPageSize(PageSize pageSize)
```


Ställ in önskad sidstorlek efter konvertering


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


Angiven sidbredd i punkter om den är satt till PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public abstract void setPageWidth(float pageWidth)
```


Ställ in önskad sidbredd


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


Angiven sidhöjd i punkter om den är satt till PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public abstract void setPageHeight(float pageHeight)
```


Ställ in önskad sidhöjd


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageHeight | float |  |

