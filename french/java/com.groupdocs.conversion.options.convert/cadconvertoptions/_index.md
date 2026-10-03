---
title: "CadConvertOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options pour la conversion vers le type Cad."
type: docs
weight: 10
url: /fr/java/com.groupdocs.conversion.options.convert/cadconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions)
```
public class CadConvertOptions extends ConvertOptions<CadFileType> implements IPagedConvertOptions
```

Options pour la conversion vers le type Cad.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [CadConvertOptions()](#CadConvertOptions--) | Initialise une nouvelle instance de la classe. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
### CadConvertOptions() {#CadConvertOptions--}
```
public CadConvertOptions()
```


Initialise une nouvelle instance de la classe.


### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Obtient le numéro de page à partir duquel commencer la conversion.


**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


Définit le numéro de page à partir duquel commencer la conversion.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


Obtient le nombre de pages à convertir à partir de PageNumber.


**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


Définit le nombre de pages à convertir à partir de PageNumber.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pagesCount | int |  |

