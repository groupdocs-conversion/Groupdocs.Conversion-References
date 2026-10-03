---
title: "CommonConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "classe astratta generica comune per le opzioni di conversione."
type: docs
weight: 11
url: /it/java/com.groupdocs.conversion.options.convert/commonconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IWatermarkedConvertOptions](../../com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions), [com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions), [com.groupdocs.conversion.options.convert.IPageRangedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagerangedconvertoptions)
```
public abstract class CommonConvertOptions<TFileType> extends ConvertOptions<TFileType> implements IWatermarkedConvertOptions, IPagedConvertOptions, IPageRangedConvertOptions
```

classe astratta generica comune per le opzioni di conversione.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWatermark()](#getWatermark--) |  |
| [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) |  |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
| [getPages()](#getPages--) |  |
| [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) |  |
### getWatermark() {#getWatermark--}
```
public WatermarkOptions getWatermark()
```


Ottiene le opzioni specifiche del watermark


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public void setWatermark(WatermarkOptions watermark)
```


Imposta le opzioni specifiche del watermark


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Ottiene il numero di pagina da cui iniziare la conversione.


**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


Imposta il numero di pagina da cui iniziare la conversione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


Ottiene il numero di pagine da convertire a partire da PageNumber.


**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


Imposta il numero di pagine da convertire a partire da PageNumber.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagesCount | int |  |

### getPages() {#getPages--}
```
public List<Integer> getPages()
```


Ottiene l'elenco degli indici di pagina da convertire. Deve essere specificato per convertire pagine specifiche.


**Returns:**
java.util.List<java.lang.Integer>
### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public void setPages(List<Integer> pages)
```


Imposta l'elenco degli indici di pagina da convertire. Deve essere specificato per convertire pagine specifiche.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pages | java.util.List<java.lang.Integer> |  |

