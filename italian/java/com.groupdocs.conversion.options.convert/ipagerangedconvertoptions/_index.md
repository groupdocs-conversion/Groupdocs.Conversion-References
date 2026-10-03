---
title: "IPageRangedConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Rappresenta le opzioni di conversione che supportano la conversione di un elenco specifico di pagine"
type: docs
weight: 52
url: /it/java/com.groupdocs.conversion.options.convert/ipagerangedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageRangedConvertOptions extends IConvertOptions
```

Rappresenta le opzioni di conversione che supportano la conversione di un elenco specifico di pagine

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPages()](#getPages--) | Ottiene l'elenco degli indici di pagina da convertire. |
|
|  | [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) | Imposta l'elenco degli indici di pagina da convertire. |
|
### getPages() {#getPages--}
```
public abstract List<Integer> getPages()
```


Ottiene l'elenco degli indici di pagina da convertire. Deve essere specificato per convertire pagine specifiche.


**Returns:**
java.util.List<java.lang.Integer> - L'elenco degli indici di pagina da convertire. Deve essere specificato per convertire pagine specifiche.

### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public abstract void setPages(List<Integer> pages)
```


Imposta l'elenco degli indici di pagina da convertire. Deve essere specificato per convertire pagine specifiche.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pages | java.util.List<java.lang.Integer> | L'elenco degli indici di pagina da convertire. Deve essere specificato per convertire pagine specifiche. |
|

