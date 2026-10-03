---
title: "CommonConvertOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "αφηρημένη γενική κοινή κλάση επιλογών μετατροπής."
type: docs
weight: 11
url: /el/java/com.groupdocs.conversion.options.convert/commonconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IWatermarkedConvertOptions](../../com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions), [com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions), [com.groupdocs.conversion.options.convert.IPageRangedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagerangedconvertoptions)
```
public abstract class CommonConvertOptions<TFileType> extends ConvertOptions<TFileType> implements IWatermarkedConvertOptions, IPagedConvertOptions, IPageRangedConvertOptions
```

αφηρημένη γενική κοινή κλάση επιλογών μετατροπής.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
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


Λαμβάνει τις επιλογές του υδατογραφήματος


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public void setWatermark(WatermarkOptions watermark)
```


Ορίζει τις επιλογές του υδατογραφήματος


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Λαμβάνει τον αριθμό σελίδας από την οποία ξεκινά η μετατροπή.


**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


Ορίζει τον αριθμό σελίδας από την οποία ξεκινά η μετατροπή.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


Λαμβάνει τον αριθμό των σελίδων προς μετατροπή ξεκινώντας από το PageNumber.


**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


Ορίζει τον αριθμό των σελίδων προς μετατροπή ξεκινώντας από το PageNumber.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pagesCount | int |  |

### getPages() {#getPages--}
```
public List<Integer> getPages()
```


Λαμβάνει τη λίστα των ευρετηρίων σελίδων που θα μετατραπούν. Πρέπει να καθοριστεί για τη μετατροπή συγκεκριμένων σελίδων.


**Returns:**
java.util.List<java.lang.Integer>
### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public void setPages(List<Integer> pages)
```


Ορίζει τη λίστα των ευρετηρίων σελίδων που θα μετατραπούν. Πρέπει να καθοριστεί για τη μετατροπή συγκεκριμένων σελίδων.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pages | java.util.List<java.lang.Integer> |  |

