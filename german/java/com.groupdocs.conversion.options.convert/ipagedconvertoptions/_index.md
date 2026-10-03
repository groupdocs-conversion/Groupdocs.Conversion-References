---
title: "IPagedConvertOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Stellt Konvertierungsoptionen dar, die es ermöglichen, die Konvertierung durch Angabe von Startseite und Seitenanzahl zu begrenzen"
type: docs
weight: 55
url: /de/java/com.groupdocs.conversion.options.convert/ipagedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPagedConvertOptions extends IConvertOptions
```

Stellt Konvertierungsoptionen dar, die es ermöglichen, die Konvertierung durch Angabe von Startseite und Seitenanzahl zu begrenzen

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Ermittelt die Seitenzahl, ab der die Konvertierung startet. |
|
|  | [setPageNumber(int pageNumber)](#setPageNumber-int-) | Setzt die Seitenzahl, ab der die Konvertierung startet. |
|
|  | [getPagesCount()](#getPagesCount--) | Ermittelt die Anzahl der Seiten, die ab PageNumber konvertiert werden sollen. |
|
|  | [setPagesCount(int pagesCount)](#setPagesCount-int-) | Setzt die Anzahl der Seiten, die ab PageNumber konvertiert werden sollen. |
|
### getPageNumber() {#getPageNumber--}
```
public abstract Integer getPageNumber()
```


Ermittelt die Seitenzahl, ab der die Konvertierung startet.


**Returns:**
java.lang.Integer - Die Seitenzahl, ab der die Konvertierung beginnen soll.

### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public abstract void setPageNumber(int pageNumber)
```


Setzt die Seitenzahl, ab der die Konvertierung startet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pageNumber | int | Die Seitenzahl, ab der die Konvertierung beginnen soll. |
|

### getPagesCount() {#getPagesCount--}
```
public abstract Integer getPagesCount()
```


Ermittelt die Anzahl der Seiten, die ab PageNumber konvertiert werden sollen.


**Returns:**
java.lang.Integer - Anzahl der Seiten, die ab PageNumber konvertiert werden sollen.

### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public abstract void setPagesCount(int pagesCount)
```


Setzt die Anzahl der Seiten, die ab PageNumber konvertiert werden sollen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pagesCount | int | Anzahl der Seiten, die ab PageNumber konvertiert werden sollen. |
|

