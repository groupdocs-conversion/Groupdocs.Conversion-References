---
title: "IPageSizeConvertOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Stellt Konvertierungsoptionen dar, die die Seitengröße unterstützen"
type: docs
weight: 54
url: /de/java/com.groupdocs.conversion.options.convert/ipagesizeconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageSizeConvertOptions extends IConvertOptions
```

Stellt Konvertierungsoptionen dar, die die Seitengröße unterstützen

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Liest die gewünschte Seitengröße nach der Konvertierung |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) | Setzt die gewünschte Seitengröße nach der Konvertierung |
|
|  | [getPageWidth()](#getPageWidth--) | Angegebene Seitenbreite in Punkten, wenn sie auf PageSize.Custom gesetzt ist |
|
|  | [setPageWidth(float pageWidth)](#setPageWidth-float-) | Setzt die gewünschte Seitenbreite |
|
|  | [getPageHeight()](#getPageHeight--) | Angegebene Seitenhöhe in Punkten, wenn sie auf PageSize.Custom gesetzt ist |
|
|  | [setPageHeight(float pageHeight)](#setPageHeight-float-) | Setzt die gewünschte Seitenhöhe |
|
### getPageSize() {#getPageSize--}
```
public abstract PageSize getPageSize()
```


Liest die gewünschte Seitengröße nach der Konvertierung


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public abstract void setPageSize(PageSize pageSize)
```


Setzt die gewünschte Seitengröße nach der Konvertierung


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


Angegebene Seitenbreite in Punkten, wenn sie auf PageSize.Custom gesetzt ist


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public abstract void setPageWidth(float pageWidth)
```


Setzt die gewünschte Seitenbreite


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


Angegebene Seitenhöhe in Punkten, wenn sie auf PageSize.Custom gesetzt ist


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public abstract void setPageHeight(float pageHeight)
```


Setzt die gewünschte Seitenhöhe


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageHeight | float |  |

