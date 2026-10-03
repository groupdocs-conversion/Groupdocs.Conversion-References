---
title: "CadConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per la conversione al tipo Cad."
type: docs
weight: 10
url: /it/java/com.groupdocs.conversion.options.convert/cadconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions)
```
public class CadConvertOptions extends ConvertOptions<CadFileType> implements IPagedConvertOptions
```

Opzioni per la conversione al tipo Cad.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [CadConvertOptions()](#CadConvertOptions--) | Inizializza una nuova istanza della classe. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
### CadConvertOptions() {#CadConvertOptions--}
```
public CadConvertOptions()
```


Inizializza una nuova istanza della classe.


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

