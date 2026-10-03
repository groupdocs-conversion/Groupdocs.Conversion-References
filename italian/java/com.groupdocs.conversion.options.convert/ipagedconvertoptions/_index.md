---
title: "IPagedConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Rappresenta le opzioni di conversione che consentono di limitare le pagine specificando la pagina iniziale e il numero di pagine"
type: docs
weight: 55
url: /it/java/com.groupdocs.conversion.options.convert/ipagedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPagedConvertOptions extends IConvertOptions
```

Rappresenta le opzioni di conversione che consentono di limitare le pagine specificando la pagina iniziale e il numero di pagine

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Ottiene il numero di pagina da cui iniziare la conversione. |
|
|  | [setPageNumber(int pageNumber)](#setPageNumber-int-) | Imposta il numero di pagina da cui iniziare la conversione. |
|
|  | [getPagesCount()](#getPagesCount--) | Ottiene il numero di pagine da convertire a partire da PageNumber. |
|
|  | [setPagesCount(int pagesCount)](#setPagesCount-int-) | Imposta il numero di pagine da convertire a partire da PageNumber. |
|
### getPageNumber() {#getPageNumber--}
```
public abstract Integer getPageNumber()
```


Ottiene il numero di pagina da cui iniziare la conversione.


**Returns:**
java.lang.Integer - Il numero di pagina da cui iniziare la conversione.

### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public abstract void setPageNumber(int pageNumber)
```


Imposta il numero di pagina da cui iniziare la conversione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pageNumber | int | Il numero di pagina da cui iniziare la conversione. |
|

### getPagesCount() {#getPagesCount--}
```
public abstract Integer getPagesCount()
```


Ottiene il numero di pagine da convertire a partire da PageNumber.


**Returns:**
java.lang.Integer - Numero di pagine da convertire a partire da PageNumber.

### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public abstract void setPagesCount(int pagesCount)
```


Imposta il numero di pagine da convertire a partire da PageNumber.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pagesCount | int | Numero di pagine da convertire a partire da PageNumber. |
|

