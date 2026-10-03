---
title: "PdfOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές για μετατροπή σε τύπο αρχείου Pdf."
type: docs
weight: 30
url: /el/java/com.groupdocs.conversion.options.convert/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptions extends ValueObject implements Serializable
```

Επιλογές για μετατροπή σε τύπο αρχείου Pdf.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | ctor |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPdfFormat()](#getPdfFormat--) | Ορίζει τη μορφή pdf του μετατρεπόμενου εγγράφου. |
|
|  | [setPdfFormat(PdfFormats value)](#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-) | Ορίζει τη μορφή pdf του μετατρεπόμενου εγγράφου. |
|
|  | [getRemovePdfACompliance()](#getRemovePdfACompliance--) | Αφαιρεί τη συμμόρφωση Pdf-A |
|
|  | [setRemovePdfACompliance(boolean value)](#setRemovePdfACompliance-boolean-) | Αφαιρεί τη συμμόρφωση Pdf-A |
|
|  | [getZoom()](#getZoom--) | Καθορίζει το επίπεδο ζουμ σε ποσοστό. |
|
|  | [setZoom(int value)](#setZoom-int-) | Καθορίζει το επίπεδο ζουμ σε ποσοστό. |
|
|  | [getLinearize()](#getLinearize--) | Γραμμικοποιεί το έγγραφο PDF για το Web |
|
|  | [setLinearize(boolean value)](#setLinearize-boolean-) | Γραμμικοποιεί το έγγραφο PDF για το Web |
|
|  | [getOptimizationOptions()](#getOptimizationOptions--) | Επιλογές βελτιστοποίησης PDF |
|
|  | [setOptimizationOptions(PdfOptimizationOptions value)](#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-) | Επιλογές βελτιστοποίησης PDF |
|
|  | [getGrayscale()](#getGrayscale--) | Μετατρέπει ένα PDF από χρωματικό χώρο RGB σε κλίμακα του γκρι |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | Μετατρέπει ένα PDF από χρωματικό χώρο RGB σε κλίμακα του γκρι |
|
|  | [getFormattingOptions()](#getFormattingOptions--) | Επιλογές μορφοποίησης PDF |
|
|  | [setFormattingOptions(PdfFormattingOptions value)](#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-) | Επιλογές μορφοποίησης PDF |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Μετα-πληροφορίες του εγγράφου PDF. |
|
| [setDocumentInfo(PdfDocumentInfo documentInfo)](#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-) |  |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


ctor


### getPdfFormat() {#getPdfFormat--}
```
public final PdfFormats getPdfFormat()
```


Ορίζει τη μορφή pdf του μετατρεπόμενου εγγράφου.


**Returns:**
[PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats)
### setPdfFormat(PdfFormats value) {#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-}
```
public final void setPdfFormat(PdfFormats value)
```


Ορίζει τη μορφή pdf του μετατρεπόμενου εγγράφου.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats) |  |

### getRemovePdfACompliance() {#getRemovePdfACompliance--}
```
public final boolean getRemovePdfACompliance()
```


Αφαιρεί τη συμμόρφωση Pdf-A


**Returns:**
boolean
### setRemovePdfACompliance(boolean value) {#setRemovePdfACompliance-boolean-}
```
public final void setRemovePdfACompliance(boolean value)
```


Αφαιρεί τη συμμόρφωση Pdf-A


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Καθορίζει το επίπεδο ζουμ σε ποσοστό. Η προεπιλογή είναι 100.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Καθορίζει το επίπεδο ζουμ σε ποσοστό. Η προεπιλογή είναι 100.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getLinearize() {#getLinearize--}
```
public final boolean getLinearize()
```


Γραμμικοποιεί το έγγραφο PDF για το Web


**Returns:**
boolean
### setLinearize(boolean value) {#setLinearize-boolean-}
```
public final void setLinearize(boolean value)
```


Γραμμικοποιεί το έγγραφο PDF για το Web


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getOptimizationOptions() {#getOptimizationOptions--}
```
public final PdfOptimizationOptions getOptimizationOptions()
```


Επιλογές βελτιστοποίησης PDF


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions)
### setOptimizationOptions(PdfOptimizationOptions value) {#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-}
```
public final void setOptimizationOptions(PdfOptimizationOptions value)
```


Επιλογές βελτιστοποίησης PDF


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Μετατρέπει ένα PDF από χρωματικό χώρο RGB σε κλίμακα του γκρι


**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Μετατρέπει ένα PDF από χρωματικό χώρο RGB σε κλίμακα του γκρι


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public final PdfFormattingOptions getFormattingOptions()
```


Επιλογές μορφοποίησης PDF


**Returns:**
[PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions)
### setFormattingOptions(PdfFormattingOptions value) {#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-}
```
public final void setFormattingOptions(PdfFormattingOptions value)
```


Επιλογές μορφοποίησης PDF


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public PdfDocumentInfo getDocumentInfo()
```


Μετα-πληροφορίες του εγγράφου PDF.


**Returns:**
[PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo)
### setDocumentInfo(PdfDocumentInfo documentInfo) {#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-}
```
public void setDocumentInfo(PdfDocumentInfo documentInfo)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| documentInfo | [PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo) |  |

