---
title: "PdfConvertOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές για μετατροπή σε τύπο αρχείου Pdf."
type: docs
weight: 25
url: /el/java/com.groupdocs.conversion.options.convert/pdfconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class PdfConvertOptions extends CommonConvertOptions<PdfFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Επιλογές για μετατροπή σε τύπο αρχείου Pdf.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PdfConvertOptions()](#PdfConvertOptions--) | Αρχικοποιεί νέα παρουσία της κλάσης [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getDpi()](#getDpi--) | Επιθυμητό DPI σελίδας μετά τη μετατροπή. |
|
|  | [setDpi(int value)](#setDpi-int-) | Επιθυμητό DPI σελίδας μετά τη μετατροπή. |
|
|  | [getPassword()](#getPassword--) | Ορίστε αυτή την ιδιότητα εάν θέλετε να προστατεύσετε το μετατρεπόμενο έγγραφο με κωδικό πρόσβασης. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ορίστε αυτή την ιδιότητα εάν θέλετε να προστατεύσετε το μετατρεπόμενο έγγραφο με κωδικό πρόσβασης. |
|
|  | [getMarginTop()](#getMarginTop--) | Επιθυμητό άνω περιθώριο σελίδας σε σημεία μετά τη μετατροπή. |
|
|  | [setMarginTop(float value)](#setMarginTop-float-) | Επιθυμητό άνω περιθώριο σελίδας σε σημεία μετά τη μετατροπή. |
|
|  | [getMarginBottom()](#getMarginBottom--) | Επιθυμητό κάτω περιθώριο σελίδας σε σημεία μετά τη μετατροπή. |
|
|  | [setMarginBottom(float value)](#setMarginBottom-float-) | Επιθυμητό κάτω περιθώριο σελίδας σε σημεία μετά τη μετατροπή. |
|
|  | [getMarginLeft()](#getMarginLeft--) | Επιθυμητό αριστερό περιθώριο σελίδας σε σημεία μετά τη μετατροπή. |
|
|  | [setMarginLeft(float value)](#setMarginLeft-float-) | Επιθυμητό αριστερό περιθώριο σελίδας σε σημεία μετά τη μετατροπή. |
|
|  | [getMarginRight()](#getMarginRight--) | Επιθυμητό δεξιό περιθώριο σελίδας σε μονάδες σημείου μετά τη μετατροπή. |
|
|  | [setMarginRight(float value)](#setMarginRight-float-) | Επιθυμητό δεξιό περιθώριο σελίδας σε μονάδες σημείου μετά τη μετατροπή. |
|
|  | [getPdfOptions()](#getPdfOptions--) | Ειδικές επιλογές μετατροπής Pdf |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-) | Ειδικές επιλογές μετατροπής Pdf |
|
|  | [getRotate()](#getRotate--) | Περιστροφή σελίδας |
|
|  | [setRotate(Rotation value)](#setRotate-com.groupdocs.conversion.options.convert.Rotation-) | Περιστροφή σελίδας |
|
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
### PdfConvertOptions() {#PdfConvertOptions--}
```
public PdfConvertOptions()
```


Αρχικοποιεί νέα παρουσία της κλάσης [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions).


### getDpi() {#getDpi--}
```
public final int getDpi()
```


Επιθυμητό DPI σελίδας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι: 96 dpi.


**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


Επιθυμητό DPI σελίδας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι: 96 dpi.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ορίστε αυτή την ιδιότητα εάν θέλετε να προστατεύσετε το μετατρεπόμενο έγγραφο με κωδικό πρόσβασης.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ορίστε αυτή την ιδιότητα εάν θέλετε να προστατεύσετε το μετατρεπόμενο έγγραφο με κωδικό πρόσβασης.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getMarginTop() {#getMarginTop--}
```
public final float getMarginTop()
```


Επιθυμητό άνω περιθώριο σελίδας σε σημεία μετά τη μετατροπή.


**Returns:**
float
### setMarginTop(float value) {#setMarginTop-float-}
```
public final void setMarginTop(float value)
```


Επιθυμητό άνω περιθώριο σελίδας σε σημεία μετά τη μετατροπή.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### getMarginBottom() {#getMarginBottom--}
```
public final float getMarginBottom()
```


Επιθυμητό κάτω περιθώριο σελίδας σε σημεία μετά τη μετατροπή.


**Returns:**
float
### setMarginBottom(float value) {#setMarginBottom-float-}
```
public final void setMarginBottom(float value)
```


Επιθυμητό κάτω περιθώριο σελίδας σε σημεία μετά τη μετατροπή.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


Επιθυμητό αριστερό περιθώριο σελίδας σε σημεία μετά τη μετατροπή.


**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


Επιθυμητό αριστερό περιθώριο σελίδας σε σημεία μετά τη μετατροπή.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


Επιθυμητό δεξιό περιθώριο σελίδας σε μονάδες σημείου μετά τη μετατροπή.


**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


Επιθυμητό δεξιό περιθώριο σελίδας σε μονάδες σημείου μετά τη μετατροπή.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Ειδικές επιλογές μετατροπής Pdf


**Returns:**
[PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Ειδικές επιλογές μετατροπής Pdf


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions) |  |

### getRotate() {#getRotate--}
```
public final Rotation getRotate()
```


Περιστροφή σελίδας


**Returns:**
[Rotation](../../com.groupdocs.conversion.options.convert/rotation)
### setRotate(Rotation value) {#setRotate-com.groupdocs.conversion.options.convert.Rotation-}
```
public final void setRotate(Rotation value)
```


Περιστροφή σελίδας


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [Rotation](../../com.groupdocs.conversion.options.convert/rotation) |  |

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

