---
title: "IPagedConvertOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Representerar konverteringsalternativ som tillåter begränsning av sidor genom att ange start sida och sidantal"
type: docs
weight: 55
url: /sv/java/com.groupdocs.conversion.options.convert/ipagedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPagedConvertOptions extends IConvertOptions
```

Representerar konverteringsalternativ som tillåter begränsning av sidor genom att ange start sida och sidantal

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Hämtar sidnumret att starta konverteringen från. |
|
|  | [setPageNumber(int pageNumber)](#setPageNumber-int-) | Ställer in sidnumret att starta konverteringen från. |
|
|  | [getPagesCount()](#getPagesCount--) | Hämtar antalet sidor att konvertera med start från PageNumber. |
|
|  | [setPagesCount(int pagesCount)](#setPagesCount-int-) | Ställer in antalet sidor att konvertera med start från PageNumber. |
|
### getPageNumber() {#getPageNumber--}
```
public abstract Integer getPageNumber()
```


Hämtar sidnumret att starta konverteringen från.


**Returns:**
java.lang.Integer - Sidnumret att börja konverteringen från.

### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public abstract void setPageNumber(int pageNumber)
```


Ställer in sidnumret att starta konverteringen från.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pageNumber | int | Sidnumret att börja konverteringen från. |
|

### getPagesCount() {#getPagesCount--}
```
public abstract Integer getPagesCount()
```


Hämtar antalet sidor att konvertera med start från PageNumber.


**Returns:**
java.lang.Integer - Antal sidor att konvertera med början från PageNumber.

### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public abstract void setPagesCount(int pagesCount)
```


Ställer in antalet sidor att konvertera med start från PageNumber.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pagesCount | int | Antal sidor att konvertera med början från PageNumber. |
|

