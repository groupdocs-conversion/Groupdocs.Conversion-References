---
title: "PdfOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor conversie naar Pdf-bestandstype."
type: docs
weight: 30
url: /nl/java/com.groupdocs.conversion.options.convert/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptions extends ValueObject implements Serializable
```

Opties voor conversie naar Pdf-bestandstype.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | ctor |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPdfFormat()](#getPdfFormat--) | Stelt het pdf-formaat van het geconverteerde document in. |
|
|  | [setPdfFormat(PdfFormats value)](#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-) | Stelt het pdf-formaat van het geconverteerde document in. |
|
|  | [getRemovePdfACompliance()](#getRemovePdfACompliance--) | Verwijdert Pdf-A-naleving |
|
|  | [setRemovePdfACompliance(boolean value)](#setRemovePdfACompliance-boolean-) | Verwijdert Pdf-A-naleving |
|
|  | [getZoom()](#getZoom--) | Specificeert het zoomniveau in procenten. |
|
|  | [setZoom(int value)](#setZoom-int-) | Specificeert het zoomniveau in procenten. |
|
|  | [getLinearize()](#getLinearize--) | Lineariseert PDF-document voor het web |
|
|  | [setLinearize(boolean value)](#setLinearize-boolean-) | Lineariseert PDF-document voor het web |
|
|  | [getOptimizationOptions()](#getOptimizationOptions--) | Pdf-optimalisatieopties |
|
|  | [setOptimizationOptions(PdfOptimizationOptions value)](#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-) | Pdf-optimalisatieopties |
|
|  | [getGrayscale()](#getGrayscale--) | Converteer een PDF van RGB-kleurruimte naar grijswaarden |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | Converteer een PDF van RGB-kleurruimte naar grijswaarden |
|
|  | [getFormattingOptions()](#getFormattingOptions--) | Pdf-opmaakopties |
|
|  | [setFormattingOptions(PdfFormattingOptions value)](#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-) | Pdf-opmaakopties |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Metagegevens van PDF-document. |
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


Stelt het pdf-formaat van het geconverteerde document in.


**Returns:**
[PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats)
### setPdfFormat(PdfFormats value) {#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-}
```
public final void setPdfFormat(PdfFormats value)
```


Stelt het pdf-formaat van het geconverteerde document in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats) |  |

### getRemovePdfACompliance() {#getRemovePdfACompliance--}
```
public final boolean getRemovePdfACompliance()
```


Verwijdert Pdf-A-naleving


**Returns:**
boolean
### setRemovePdfACompliance(boolean value) {#setRemovePdfACompliance-boolean-}
```
public final void setRemovePdfACompliance(boolean value)
```


Verwijdert Pdf-A-naleving


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Specificeert het zoomniveau in procenten. Standaard is 100.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Specificeert het zoomniveau in procenten. Standaard is 100.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getLinearize() {#getLinearize--}
```
public final boolean getLinearize()
```


Lineariseert PDF-document voor het web


**Returns:**
boolean
### setLinearize(boolean value) {#setLinearize-boolean-}
```
public final void setLinearize(boolean value)
```


Lineariseert PDF-document voor het web


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getOptimizationOptions() {#getOptimizationOptions--}
```
public final PdfOptimizationOptions getOptimizationOptions()
```


Pdf-optimalisatieopties


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions)
### setOptimizationOptions(PdfOptimizationOptions value) {#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-}
```
public final void setOptimizationOptions(PdfOptimizationOptions value)
```


Pdf-optimalisatieopties


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Converteer een PDF van RGB-kleurruimte naar grijswaarden


**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Converteer een PDF van RGB-kleurruimte naar grijswaarden


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public final PdfFormattingOptions getFormattingOptions()
```


Pdf-opmaakopties


**Returns:**
[PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions)
### setFormattingOptions(PdfFormattingOptions value) {#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-}
```
public final void setFormattingOptions(PdfFormattingOptions value)
```


Pdf-opmaakopties


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public PdfDocumentInfo getDocumentInfo()
```


Metagegevens van PDF-document.


**Returns:**
[PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo)
### setDocumentInfo(PdfDocumentInfo documentInfo) {#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-}
```
public void setDocumentInfo(PdfDocumentInfo documentInfo)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| documentInfo | [PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo) |  |

