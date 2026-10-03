---
title: "EBookConvertOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές για μετατροπή σε τύπο αρχείου EBook."
type: docs
weight: 14
url: /el/java/com.groupdocs.conversion.options.convert/ebookconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class EBookConvertOptions extends CommonConvertOptions<EBookFileType> implements IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Επιλογές για μετατροπή σε τύπο αρχείου EBook.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [EBookConvertOptions()](#EBookConvertOptions--) | Αρχικοποιεί νέα παρουσία της κλάσης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
### EBookConvertOptions() {#EBookConvertOptions--}
```
public EBookConvertOptions()
```


Αρχικοποιεί νέα παρουσία της κλάσης.


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Λαμβάνει επιθυμητό μέγεθος σελίδας μετά τη μετατροπή


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Ορίστε επιθυμητό μέγεθος σελίδας μετά τη μετατροπή


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Καθορισμένο πλάτος σελίδας σε μονάδες σημείου εάν έχει οριστεί σε PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


Ορίστε επιθυμητό πλάτος σελίδας


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Καθορισμένο ύψος σελίδας σε μονάδες σημείου εάν έχει οριστεί σε PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


Ορίστε επιθυμητό ύψος σελίδας


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pageHeight | float |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


Λαμβάνει προσανατολισμό σελίδας μετά τη μετατροπή


**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


Ορίζει επιθυμητό προσανατολισμό σελίδας μετά τη μετατροπή


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

