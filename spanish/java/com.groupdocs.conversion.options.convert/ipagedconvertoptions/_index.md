---
title: "IPagedConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Representa las opciones de conversión que permiten limitar la conversión especificando la página de inicio y la cantidad de páginas"
type: docs
weight: 55
url: /es/java/com.groupdocs.conversion.options.convert/ipagedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPagedConvertOptions extends IConvertOptions
```

Representa las opciones de conversión que permiten limitar la conversión especificando la página de inicio y la cantidad de páginas

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Obtiene el número de página desde el cual iniciar la conversión. |
|
|  | [setPageNumber(int pageNumber)](#setPageNumber-int-) | Establece el número de página desde el cual iniciar la conversión. |
|
|  | [getPagesCount()](#getPagesCount--) | Obtiene el número de páginas a convertir a partir de PageNumber. |
|
|  | [setPagesCount(int pagesCount)](#setPagesCount-int-) | Establece el número de páginas a convertir a partir de PageNumber. |
|
### getPageNumber() {#getPageNumber--}
```
public abstract Integer getPageNumber()
```


Obtiene el número de página desde el cual iniciar la conversión.


**Returns:**
java.lang.Integer - El número de página desde el cual iniciar la conversión.

### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public abstract void setPageNumber(int pageNumber)
```


Establece el número de página desde el cual iniciar la conversión.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pageNumber | int | El número de página desde el cual iniciar la conversión. |
|

### getPagesCount() {#getPagesCount--}
```
public abstract Integer getPagesCount()
```


Obtiene el número de páginas a convertir a partir de PageNumber.


**Returns:**
java.lang.Integer - Número de páginas a convertir a partir de PageNumber.

### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public abstract void setPagesCount(int pagesCount)
```


Establece el número de páginas a convertir a partir de PageNumber.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pagesCount | int | Número de páginas a convertir a partir de PageNumber. |
|

