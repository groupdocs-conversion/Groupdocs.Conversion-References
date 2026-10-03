---
title: "CommonConvertOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "abstracte generieke algemene conversieoptiesklasse."
type: docs
weight: 11
url: /nl/java/com.groupdocs.conversion.options.convert/commonconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IWatermarkedConvertOptions](../../com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions), [com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions), [com.groupdocs.conversion.options.convert.IPageRangedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagerangedconvertoptions)
```
public abstract class CommonConvertOptions<TFileType> extends ConvertOptions<TFileType> implements IWatermarkedConvertOptions, IPagedConvertOptions, IPageRangedConvertOptions
```

abstracte generieke algemene conversieoptiesklasse.

## Methoden

| Methode | Beschrijving |
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


Haalt watermerk‑specifieke opties op


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public void setWatermark(WatermarkOptions watermark)
```


Stelt watermerk‑specifieke opties in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) |  |

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

### getPages() {#getPages--}
```
public List<Integer> getPages()
```


Haalt de lijst met paginanummers op die moeten worden geconverteerd. Moet worden opgegeven om specifieke pagina's te converteren.


**Returns:**
java.util.List<java.lang.Integer>
### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public void setPages(List<Integer> pages)
```


Stelt de lijst met paginanummers in die moeten worden geconverteerd. Moet worden opgegeven om specifieke pagina's te converteren.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pages | java.util.List<java.lang.Integer> |  |

