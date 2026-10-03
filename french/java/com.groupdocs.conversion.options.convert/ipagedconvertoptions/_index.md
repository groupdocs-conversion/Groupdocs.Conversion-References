---
title: "IPagedConvertOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Représente les options de conversion qui permettent de limiter les pages en spécifiant la page de départ et le nombre de pages."
type: docs
weight: 55
url: /fr/java/com.groupdocs.conversion.options.convert/ipagedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPagedConvertOptions extends IConvertOptions
```

Représente les options de conversion qui permettent de limiter les pages en spécifiant la page de départ et le nombre de pages.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Obtient le numéro de page à partir duquel commencer la conversion. |
|
|  | [setPageNumber(int pageNumber)](#setPageNumber-int-) | Définit le numéro de page à partir duquel commencer la conversion. |
|
|  | [getPagesCount()](#getPagesCount--) | Obtient le nombre de pages à convertir à partir de PageNumber. |
|
|  | [setPagesCount(int pagesCount)](#setPagesCount-int-) | Définit le nombre de pages à convertir à partir de PageNumber. |
|
### getPageNumber() {#getPageNumber--}
```
public abstract Integer getPageNumber()
```


Obtient le numéro de page à partir duquel commencer la conversion.


**Returns:**
java.lang.Integer - Le numéro de page à partir duquel commencer la conversion.

### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public abstract void setPageNumber(int pageNumber)
```


Définit le numéro de page à partir duquel commencer la conversion.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pageNumber | int | Le numéro de page à partir duquel commencer la conversion. |
|

### getPagesCount() {#getPagesCount--}
```
public abstract Integer getPagesCount()
```


Obtient le nombre de pages à convertir à partir de PageNumber.


**Returns:**
java.lang.Integer - Nombre de pages à convertir à partir de PageNumber.

### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public abstract void setPagesCount(int pagesCount)
```


Définit le nombre de pages à convertir à partir de PageNumber.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pagesCount | int | Nombre de pages à convertir à partir de PageNumber. |
|

