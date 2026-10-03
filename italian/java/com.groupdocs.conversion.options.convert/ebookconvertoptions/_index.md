---
title: "EBookConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per la conversione al tipo di file EBook."
type: docs
weight: 14
url: /it/java/com.groupdocs.conversion.options.convert/ebookconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class EBookConvertOptions extends CommonConvertOptions<EBookFileType> implements IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Opzioni per la conversione al tipo di file EBook.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [EBookConvertOptions()](#EBookConvertOptions--) | Inizializza una nuova istanza della classe. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
### EBookConvertOptions() {#EBookConvertOptions--}
```
public EBookConvertOptions()
```


Inizializza una nuova istanza della classe.


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Ottiene le dimensioni della pagina desiderate dopo la conversione


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Imposta le dimensioni della pagina desiderate dopo la conversione


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Larghezza della pagina specificata in punti se impostata su PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


Imposta la larghezza della pagina desiderata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Altezza della pagina specificata in punti se impostata su PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


Imposta l'altezza della pagina desiderata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageHeight | float |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


Ottiene l'orientamento della pagina dopo la conversione


**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


Imposta l'orientamento della pagina desiderato dopo la conversione


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

