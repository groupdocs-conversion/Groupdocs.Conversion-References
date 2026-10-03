---
title: "IPageSizeConvertOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Geeft de conversie‑opties weer die paginagrootte ondersteunen."
type: docs
weight: 54
url: /nl/java/com.groupdocs.conversion.options.convert/ipagesizeconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageSizeConvertOptions extends IConvertOptions
```

Geeft de conversie‑opties weer die paginagrootte ondersteunen.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Haalt gewenste paginagrootte op na conversie |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) | Stel gewenste paginagrootte in na conversie |
|
|  | [getPageWidth()](#getPageWidth--) | Gespecificeerde paginabreedte in punten als deze is ingesteld op PageSize.Custom |
|
|  | [setPageWidth(float pageWidth)](#setPageWidth-float-) | Stel gewenste paginabreedte in |
|
|  | [getPageHeight()](#getPageHeight--) | Gespecificeerde paginahoogte in punten als deze is ingesteld op PageSize.Custom |
|
|  | [setPageHeight(float pageHeight)](#setPageHeight-float-) | Stel gewenste paginahoogte in |
|
### getPageSize() {#getPageSize--}
```
public abstract PageSize getPageSize()
```


Haalt gewenste paginagrootte op na conversie


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public abstract void setPageSize(PageSize pageSize)
```


Stel gewenste paginagrootte in na conversie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


Gespecificeerde paginabreedte in punten als deze is ingesteld op PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public abstract void setPageWidth(float pageWidth)
```


Stel gewenste paginabreedte in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


Gespecificeerde paginahoogte in punten als deze is ingesteld op PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public abstract void setPageHeight(float pageHeight)
```


Stel gewenste paginahoogte in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageHeight | float |  |

