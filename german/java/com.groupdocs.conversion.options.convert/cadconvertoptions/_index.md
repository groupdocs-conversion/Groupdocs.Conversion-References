---
title: "CadConvertOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen für die Konvertierung zum Cad-Typ."
type: docs
weight: 10
url: /de/java/com.groupdocs.conversion.options.convert/cadconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions)
```
public class CadConvertOptions extends ConvertOptions<CadFileType> implements IPagedConvertOptions
```

Optionen für die Konvertierung zum Cad-Typ.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [CadConvertOptions()](#CadConvertOptions--) | Initialisiert eine neue Instanz der Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
### CadConvertOptions() {#CadConvertOptions--}
```
public CadConvertOptions()
```


Initialisiert eine neue Instanz der Klasse.


### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Ermittelt die Seitenzahl, ab der die Konvertierung startet.


**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


Setzt die Seitenzahl, ab der die Konvertierung startet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


Ermittelt die Anzahl der Seiten, die ab PageNumber konvertiert werden sollen.


**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


Setzt die Anzahl der Seiten, die ab PageNumber konvertiert werden sollen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pagesCount | int |  |

