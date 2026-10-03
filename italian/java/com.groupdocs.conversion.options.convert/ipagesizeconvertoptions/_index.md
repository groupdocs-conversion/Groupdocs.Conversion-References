---
title: "IPageSizeConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Rappresenta le opzioni di conversione che supportano le dimensioni della pagina"
type: docs
weight: 54
url: /it/java/com.groupdocs.conversion.options.convert/ipagesizeconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageSizeConvertOptions extends IConvertOptions
```

Rappresenta le opzioni di conversione che supportano le dimensioni della pagina

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Ottiene le dimensioni della pagina desiderate dopo la conversione |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) | Imposta le dimensioni della pagina desiderate dopo la conversione |
|
|  | [getPageWidth()](#getPageWidth--) | Larghezza della pagina specificata in punti se impostata su PageSize.Custom |
|
|  | [setPageWidth(float pageWidth)](#setPageWidth-float-) | Imposta la larghezza della pagina desiderata |
|
|  | [getPageHeight()](#getPageHeight--) | Altezza della pagina specificata in punti se impostata su PageSize.Custom |
|
|  | [setPageHeight(float pageHeight)](#setPageHeight-float-) | Imposta l'altezza della pagina desiderata |
|
### getPageSize() {#getPageSize--}
```
public abstract PageSize getPageSize()
```


Ottiene le dimensioni della pagina desiderate dopo la conversione


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public abstract void setPageSize(PageSize pageSize)
```


Imposta le dimensioni della pagina desiderate dopo la conversione


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


Larghezza della pagina specificata in punti se impostata su PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public abstract void setPageWidth(float pageWidth)
```


Imposta la larghezza della pagina desiderata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


Altezza della pagina specificata in punti se impostata su PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public abstract void setPageHeight(float pageHeight)
```


Imposta l'altezza della pagina desiderata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageHeight | float |  |

