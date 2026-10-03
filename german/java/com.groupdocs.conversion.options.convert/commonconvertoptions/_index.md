---
title: "CommonConvertOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "abstrakte generische gemeinsame Konvertierungsoptionenklasse."
type: docs
weight: 11
url: /de/java/com.groupdocs.conversion.options.convert/commonconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IWatermarkedConvertOptions](../../com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions), [com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions), [com.groupdocs.conversion.options.convert.IPageRangedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagerangedconvertoptions)
```
public abstract class CommonConvertOptions<TFileType> extends ConvertOptions<TFileType> implements IWatermarkedConvertOptions, IPagedConvertOptions, IPageRangedConvertOptions
```

abstrakte generische gemeinsame Konvertierungsoptionenklasse.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWatermark()](#getWatermark--) |  |
| [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) |  |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
| [getPages()](#getPages--) |  |
| [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) |  |
### getWatermark() {#getWatermark--}
```
public WatermarkOptions getWatermark()
```


Ruft wasserzeichenspezifische Optionen ab


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public void setWatermark(WatermarkOptions watermark)
```


Setzt wasserzeichenspezifische Optionen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) |  |

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

### getPages() {#getPages--}
```
public List<Integer> getPages()
```


Ruft die Liste der Seitenindizes ab, die konvertiert werden sollen. Sollte angegeben werden, um bestimmte Seiten zu konvertieren.


**Returns:**
java.util.List<java.lang.Integer>
### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public void setPages(List<Integer> pages)
```


Setzt die Liste der Seitenindizes, die konvertiert werden sollen. Sollte angegeben werden, um bestimmte Seiten zu konvertieren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pages | java.util.List<java.lang.Integer> |  |

