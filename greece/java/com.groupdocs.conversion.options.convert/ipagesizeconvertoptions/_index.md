---
title: "IPageSizeConvertOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Αντιπροσωπεύει τις επιλογές μετατροπής που υποστηρίζουν μέγεθος σελίδας"
type: docs
weight: 54
url: /el/java/com.groupdocs.conversion.options.convert/ipagesizeconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageSizeConvertOptions extends IConvertOptions
```

Αντιπροσωπεύει τις επιλογές μετατροπής που υποστηρίζουν μέγεθος σελίδας

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Λαμβάνει επιθυμητό μέγεθος σελίδας μετά τη μετατροπή |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) | Ορίστε επιθυμητό μέγεθος σελίδας μετά τη μετατροπή |
|
|  | [getPageWidth()](#getPageWidth--) | Καθορισμένο πλάτος σελίδας σε μονάδες σημείου εάν έχει οριστεί σε PageSize.Custom |
|
|  | [setPageWidth(float pageWidth)](#setPageWidth-float-) | Ορίστε επιθυμητό πλάτος σελίδας |
|
|  | [getPageHeight()](#getPageHeight--) | Καθορισμένο ύψος σελίδας σε μονάδες σημείου εάν έχει οριστεί σε PageSize.Custom |
|
|  | [setPageHeight(float pageHeight)](#setPageHeight-float-) | Ορίστε επιθυμητό ύψος σελίδας |
|
### getPageSize() {#getPageSize--}
```
public abstract PageSize getPageSize()
```


Λαμβάνει επιθυμητό μέγεθος σελίδας μετά τη μετατροπή


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public abstract void setPageSize(PageSize pageSize)
```


Ορίστε επιθυμητό μέγεθος σελίδας μετά τη μετατροπή


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


Καθορισμένο πλάτος σελίδας σε μονάδες σημείου εάν έχει οριστεί σε PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public abstract void setPageWidth(float pageWidth)
```


Ορίστε επιθυμητό πλάτος σελίδας


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


Καθορισμένο ύψος σελίδας σε μονάδες σημείου εάν έχει οριστεί σε PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public abstract void setPageHeight(float pageHeight)
```


Ορίστε επιθυμητό ύψος σελίδας


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pageHeight | float |  |

