---
title: "IPagedConvertOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Geeft de conversie‑opties weer die het beperken van pagina's mogelijk maken door een startpagina en aantal pagina's op te geven."
type: docs
weight: 55
url: /nl/java/com.groupdocs.conversion.options.convert/ipagedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPagedConvertOptions extends IConvertOptions
```

Geeft de conversie‑opties weer die het beperken van pagina's mogelijk maken door een startpagina en aantal pagina's op te geven.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Haalt het paginanummer op waarvan de conversie moet beginnen. |
|
|  | [setPageNumber(int pageNumber)](#setPageNumber-int-) | Stelt het paginanummer in waarvan de conversie moet beginnen. |
|
|  | [getPagesCount()](#getPagesCount--) | Haalt het aantal pagina's op dat moet worden geconverteerd beginnend bij PageNumber. |
|
|  | [setPagesCount(int pagesCount)](#setPagesCount-int-) | Stelt het aantal pagina's in dat moet worden geconverteerd beginnend bij PageNumber. |
|
### getPageNumber() {#getPageNumber--}
```
public abstract Integer getPageNumber()
```


Haalt het paginanummer op waarvan de conversie moet beginnen.


**Returns:**
java.lang.Integer - Het paginanummer om de conversie vanaf te starten.

### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public abstract void setPageNumber(int pageNumber)
```


Stelt het paginanummer in waarvan de conversie moet beginnen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pageNumber | int | Het paginanummer om de conversie vanaf te starten. |
|

### getPagesCount() {#getPagesCount--}
```
public abstract Integer getPagesCount()
```


Haalt het aantal pagina's op dat moet worden geconverteerd beginnend bij PageNumber.


**Returns:**
java.lang.Integer - Aantal pagina's om te converteren, beginnend bij PageNumber.

### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public abstract void setPagesCount(int pagesCount)
```


Stelt het aantal pagina's in dat moet worden geconverteerd beginnend bij PageNumber.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pagesCount | int | Aantal pagina's om te converteren, beginnend bij PageNumber. |
|

