---
title: "PdfOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för konvertering till Pdf-filtyp."
type: docs
weight: 30
url: /sv/java/com.groupdocs.conversion.options.convert/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptions extends ValueObject implements Serializable
```

Alternativ för konvertering till Pdf-filtyp.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | ctor |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPdfFormat()](#getPdfFormat--) | Ställer in pdf-formatet för det konverterade dokumentet. |
|
|  | [setPdfFormat(PdfFormats value)](#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-) | Ställer in pdf-formatet för det konverterade dokumentet. |
|
|  | [getRemovePdfACompliance()](#getRemovePdfACompliance--) | Tar bort Pdf-A-efterlevnad |
|
|  | [setRemovePdfACompliance(boolean value)](#setRemovePdfACompliance-boolean-) | Tar bort Pdf-A-efterlevnad |
|
|  | [getZoom()](#getZoom--) | Anger zoomnivån i procent. |
|
|  | [setZoom(int value)](#setZoom-int-) | Anger zoomnivån i procent. |
|
|  | [getLinearize()](#getLinearize--) | Lineariserar PDF-dokument för webben |
|
|  | [setLinearize(boolean value)](#setLinearize-boolean-) | Lineariserar PDF-dokument för webben |
|
|  | [getOptimizationOptions()](#getOptimizationOptions--) | Alternativ för PDF-optimering |
|
|  | [setOptimizationOptions(PdfOptimizationOptions value)](#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-) | Alternativ för PDF-optimering |
|
|  | [getGrayscale()](#getGrayscale--) | Konvertera en PDF från RGB-färgrymd till gråskala |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | Konvertera en PDF från RGB-färgrymd till gråskala |
|
|  | [getFormattingOptions()](#getFormattingOptions--) | Alternativ för PDF-formatering |
|
|  | [setFormattingOptions(PdfFormattingOptions value)](#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-) | Alternativ för PDF-formatering |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Metainformation för PDF-dokument. |
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


Ställer in pdf-formatet för det konverterade dokumentet.


**Returns:**
[PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats)
### setPdfFormat(PdfFormats value) {#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-}
```
public final void setPdfFormat(PdfFormats value)
```


Ställer in pdf-formatet för det konverterade dokumentet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats) |  |

### getRemovePdfACompliance() {#getRemovePdfACompliance--}
```
public final boolean getRemovePdfACompliance()
```


Tar bort Pdf-A-efterlevnad


**Returns:**
boolean
### setRemovePdfACompliance(boolean value) {#setRemovePdfACompliance-boolean-}
```
public final void setRemovePdfACompliance(boolean value)
```


Tar bort Pdf-A-efterlevnad


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Anger zoomnivån i procent. Standard är 100.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Anger zoomnivån i procent. Standard är 100.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLinearize() {#getLinearize--}
```
public final boolean getLinearize()
```


Lineariserar PDF-dokument för webben


**Returns:**
boolean
### setLinearize(boolean value) {#setLinearize-boolean-}
```
public final void setLinearize(boolean value)
```


Lineariserar PDF-dokument för webben


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getOptimizationOptions() {#getOptimizationOptions--}
```
public final PdfOptimizationOptions getOptimizationOptions()
```


Alternativ för PDF-optimering


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions)
### setOptimizationOptions(PdfOptimizationOptions value) {#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-}
```
public final void setOptimizationOptions(PdfOptimizationOptions value)
```


Alternativ för PDF-optimering


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Konvertera en PDF från RGB-färgrymd till gråskala


**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Konvertera en PDF från RGB-färgrymd till gråskala


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public final PdfFormattingOptions getFormattingOptions()
```


Alternativ för PDF-formatering


**Returns:**
[PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions)
### setFormattingOptions(PdfFormattingOptions value) {#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-}
```
public final void setFormattingOptions(PdfFormattingOptions value)
```


Alternativ för PDF-formatering


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public PdfDocumentInfo getDocumentInfo()
```


Metainformation för PDF-dokument.


**Returns:**
[PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo)
### setDocumentInfo(PdfDocumentInfo documentInfo) {#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-}
```
public void setDocumentInfo(PdfDocumentInfo documentInfo)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documentInfo | [PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo) |  |

