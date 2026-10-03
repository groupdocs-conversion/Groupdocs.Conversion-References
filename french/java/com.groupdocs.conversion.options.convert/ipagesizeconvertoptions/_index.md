---
title: "IPageSizeConvertOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Représente les options de conversion qui prennent en charge la taille de page."
type: docs
weight: 54
url: /fr/java/com.groupdocs.conversion.options.convert/ipagesizeconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageSizeConvertOptions extends IConvertOptions
```

Représente les options de conversion qui prennent en charge la taille de page.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Obtient la taille de page souhaitée après conversion |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) | Définit la taille de page souhaitée après conversion |
|
|  | [getPageWidth()](#getPageWidth--) | Largeur de page spécifiée en points si elle est définie sur PageSize.Custom |
|
|  | [setPageWidth(float pageWidth)](#setPageWidth-float-) | Définit la largeur de page souhaitée |
|
|  | [getPageHeight()](#getPageHeight--) | Hauteur de page spécifiée en points si elle est définie sur PageSize.Custom |
|
|  | [setPageHeight(float pageHeight)](#setPageHeight-float-) | Définit la hauteur de page souhaitée |
|
### getPageSize() {#getPageSize--}
```
public abstract PageSize getPageSize()
```


Obtient la taille de page souhaitée après conversion


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public abstract void setPageSize(PageSize pageSize)
```


Définit la taille de page souhaitée après conversion


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


Largeur de page spécifiée en points si elle est définie sur PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public abstract void setPageWidth(float pageWidth)
```


Définit la largeur de page souhaitée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


Hauteur de page spécifiée en points si elle est définie sur PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public abstract void setPageHeight(float pageHeight)
```


Définit la hauteur de page souhaitée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageHeight | float |  |

