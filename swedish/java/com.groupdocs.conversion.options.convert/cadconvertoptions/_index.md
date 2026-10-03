---
title: "CadConvertOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för konvertering till Cad-typ."
type: docs
weight: 10
url: /sv/java/com.groupdocs.conversion.options.convert/cadconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions)
```
public class CadConvertOptions extends ConvertOptions<CadFileType> implements IPagedConvertOptions
```

Alternativ för konvertering till Cad-typ.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [CadConvertOptions()](#CadConvertOptions--) | Initierar en ny instans av klassen. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
### CadConvertOptions() {#CadConvertOptions--}
```
public CadConvertOptions()
```


Initierar en ny instans av klassen.


### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Hämtar sidnumret att starta konverteringen från.


**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


Ställer in sidnumret att starta konverteringen från.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


Hämtar antalet sidor att konvertera med start från PageNumber.


**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


Ställer in antalet sidor att konvertera med start från PageNumber.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pagesCount | int |  |

