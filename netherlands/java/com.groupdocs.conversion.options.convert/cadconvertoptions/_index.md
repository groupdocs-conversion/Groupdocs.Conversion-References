---
title: "CadConvertOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor conversie naar Cad-type."
type: docs
weight: 10
url: /nl/java/com.groupdocs.conversion.options.convert/cadconvertoptions/
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
|  | [CadConvertOptions()](#CadConvertOptions--) | Initialiseert een nieuwe instantie van de klasse. |
|
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


Initialiseert een nieuwe instantie van de klasse.


### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Haalt het paginanummer op waarvan de conversie moet beginnen.


**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


Stelt het paginanummer in waarvan de conversie moet beginnen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


Haalt het aantal pagina's op dat moet worden geconverteerd beginnend bij PageNumber.


**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


Stelt het aantal pagina's in dat moet worden geconverteerd beginnend bij PageNumber.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pagesCount | int |  |

