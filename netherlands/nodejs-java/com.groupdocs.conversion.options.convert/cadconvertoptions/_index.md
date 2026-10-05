---
title: "CadConvertOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor conversie naar Cad-type."
type: docs
weight: 10
url: /nl/nodejs-java/com.groupdocs.conversion.options.convert/cadconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions)
```
public class CadConvertOptions extends ConvertOptions<CadFileType> implements IPagedConvertOptions
```

Opties voor conversie naar Cad-type.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CadConvertOptions()](#CadConvertOptions--) | Initialiseert een nieuw exemplaar van de class. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
### CadConvertOptions() {#CadConvertOptions--}
```
public CadConvertOptions()
```


Initialiseert een nieuw exemplaar van de class.

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Haalt het paginanummer op om de conversie vanaf te starten.

**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


Stelt het paginanummer in om de conversie vanaf te starten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


Haalt het aantal pagina's op om te converteren beginnend bij PageNumber.

**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


Stelt het aantal pagina's in dat moet worden geconverteerd, beginnend bij PageNumber.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pagesCount | int |  |

