---
title: "CadConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para conversión a tipo Cad."
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.conversion.options.convert/cadconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions)
```
public class CadConvertOptions extends ConvertOptions<CadFileType> implements IPagedConvertOptions
```

Opciones para conversión a tipo Cad.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CadConvertOptions()](#CadConvertOptions--) | Inicializa una nueva instancia de  clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
### CadConvertOptions() {#CadConvertOptions--}
```
public CadConvertOptions()
```


Inicializa una nueva instancia de  clase.

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Obtiene el número de página desde el cual iniciar la conversión.

**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


Establece el número de página desde el cual iniciar la conversión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


Obtiene el número de páginas a convertir a partir de PageNumber.

**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


Establece el número de páginas a convertir a partir de PageNumber.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pagesCount | int |  |

