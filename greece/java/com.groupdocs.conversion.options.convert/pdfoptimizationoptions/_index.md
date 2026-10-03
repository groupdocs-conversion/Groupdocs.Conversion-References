---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ορίζει τις επιλογές βελτιστοποίησης Pdf."
type: docs
weight: 29
url: /el/java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptimizationOptions extends ValueObject implements Serializable
```

Ορίζει τις επιλογές βελτιστοποίησης Pdf.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Αρχικοποιεί νέα παρουσία της κλάσης [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | Σύνδεση διπλότυπων ροών |
|
|  | [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | Σύνδεση διπλότυπων ροών |
|
|  | [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | Αφαίρεση αχρησιμοποίητων αντικειμένων |
|
|  | [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | Αφαίρεση αχρησιμοποίητων αντικειμένων |
|
|  | [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | Αφαίρεση αχρησιμοποίητων ροών |
|
|  | [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | Αφαίρεση αχρησιμοποίητων ροών |
|
|  | [getCompressImages()](#getCompressImages--) | Εάν το CompressImages οριστεί σε |
true
, όλες οι εικόνες στο έγγραφο επανασυμπιέζονται.
|
|  | [setCompressImages(boolean value)](#setCompressImages-boolean-) | Εάν το CompressImages οριστεί σε |
true
, όλες οι εικόνες στο έγγραφο επανασυμπιέζονται.
|
|  | [getImageQuality()](#getImageQuality--) | Τιμή σε ποσοστό όπου το 100% αντιστοιχεί σε αμετάβλητη ποιότητα και μέγεθος εικόνας. |
|
|  | [setImageQuality(int value)](#setImageQuality-int-) | Τιμή σε ποσοστό όπου το 100% αντιστοιχεί σε αμετάβλητη ποιότητα και μέγεθος εικόνας. |
|
|  | [getUnembedFonts()](#getUnembedFonts--) | Κάντε τις γραμματοσειρές μη ενσωματωμένες εάν οριστεί σε true |
|
|  | [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | Κάντε τις γραμματοσειρές μη ενσωματωμένες εάν οριστεί σε true |
|
| [getFontSubsetStrategy()](#getFontSubsetStrategy--) |  |
|  | [setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)](#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-) | Ορίστε τη στρατηγική υποσυνόλου γραμματοσειρών |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Αρχικοποιεί νέα παρουσία της κλάσης [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions).


### getLinkDuplicateStreams() {#getLinkDuplicateStreams--}
```
public final boolean getLinkDuplicateStreams()
```


Σύνδεση διπλότυπων ροών


**Returns:**
boolean
### setLinkDuplicateStreams(boolean value) {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```


Σύνδεση διπλότυπων ροών


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


Αφαίρεση αχρησιμοποίητων αντικειμένων


**Returns:**
boolean
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


Αφαίρεση αχρησιμοποίητων αντικειμένων


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


Αφαίρεση αχρησιμοποίητων ροών


**Returns:**
boolean
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


Αφαίρεση αχρησιμοποίητων ροών


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


Εάν το CompressImages οριστεί σε
true
, όλες οι εικόνες στο έγγραφο επανασυμπιέζονται. Η συμπίεση ορίζεται από την ιδιότητα ImageQuality.


**Returns:**
boolean
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


Εάν το CompressImages οριστεί σε
true
, όλες οι εικόνες στο έγγραφο επανασυμπιέζονται. Η συμπίεση ορίζεται από την ιδιότητα ImageQuality.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Τιμή σε ποσοστό όπου το 100% αντιστοιχεί σε αμετάβλητη ποιότητα και μέγεθος εικόνας. Για να μειώσετε το μέγεθος της εικόνας, ορίστε αυτή την ιδιότητα σε τιμή μικρότερη από 100.


**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Τιμή σε ποσοστό όπου το 100% αντιστοιχεί σε αμετάβλητη ποιότητα και μέγεθος εικόνας. Για να μειώσετε το μέγεθος της εικόνας, ορίστε αυτή την ιδιότητα σε τιμή μικρότερη από 100.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


Κάντε τις γραμματοσειρές μη ενσωματωμένες εάν οριστεί σε true


**Returns:**
boolean
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


Κάντε τις γραμματοσειρές μη ενσωματωμένες εάν οριστεί σε true


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getFontSubsetStrategy() {#getFontSubsetStrategy--}
```
public PdfFontSubsetStrategy getFontSubsetStrategy()
```




**Returns:**
[PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy)
### setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy) {#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-}
```
public void setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)
```


Ορίστε τη στρατηγική υποσυνόλου γραμματοσειρών


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| fontSubsetStrategy | [PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy) |  |

