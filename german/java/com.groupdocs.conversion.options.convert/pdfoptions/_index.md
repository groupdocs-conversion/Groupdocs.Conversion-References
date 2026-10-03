---
title: "PdfOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen für die Konvertierung zum Pdf-Dateityp."
type: docs
weight: 30
url: /de/java/com.groupdocs.conversion.options.convert/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptions extends ValueObject implements Serializable
```

Optionen für die Konvertierung zum Pdf-Dateityp.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | ctor |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPdfFormat()](#getPdfFormat--) | Setzt das PDF-Format des konvertierten Dokuments. |
|
|  | [setPdfFormat(PdfFormats value)](#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-) | Setzt das PDF-Format des konvertierten Dokuments. |
|
|  | [getRemovePdfACompliance()](#getRemovePdfACompliance--) | Entfernt die PDF/A-Konformität. |
|
|  | [setRemovePdfACompliance(boolean value)](#setRemovePdfACompliance-boolean-) | Entfernt die PDF/A-Konformität. |
|
|  | [getZoom()](#getZoom--) | Gibt den Zoom‑Wert in Prozent an. |
|
|  | [setZoom(int value)](#setZoom-int-) | Gibt den Zoom‑Wert in Prozent an. |
|
|  | [getLinearize()](#getLinearize--) | Linearisiert das PDF-Dokument für das Web. |
|
|  | [setLinearize(boolean value)](#setLinearize-boolean-) | Linearisiert das PDF-Dokument für das Web. |
|
|  | [getOptimizationOptions()](#getOptimizationOptions--) | PDF-Optimierungsoptionen |
|
|  | [setOptimizationOptions(PdfOptimizationOptions value)](#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-) | PDF-Optimierungsoptionen |
|
|  | [getGrayscale()](#getGrayscale--) | Konvertiert ein PDF vom RGB-Farbraum in Graustufen |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | Konvertiert ein PDF vom RGB-Farbraum in Graustufen |
|
|  | [getFormattingOptions()](#getFormattingOptions--) | PDF-Formatierungsoptionen |
|
|  | [setFormattingOptions(PdfFormattingOptions value)](#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-) | PDF-Formatierungsoptionen |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Metainformationen des PDF-Dokuments. |
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


Setzt das PDF-Format des konvertierten Dokuments.


**Returns:**
[PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats)
### setPdfFormat(PdfFormats value) {#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-}
```
public final void setPdfFormat(PdfFormats value)
```


Setzt das PDF-Format des konvertierten Dokuments.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats) |  |

### getRemovePdfACompliance() {#getRemovePdfACompliance--}
```
public final boolean getRemovePdfACompliance()
```


Entfernt die PDF/A-Konformität.


**Returns:**
boolean
### setRemovePdfACompliance(boolean value) {#setRemovePdfACompliance-boolean-}
```
public final void setRemovePdfACompliance(boolean value)
```


Entfernt die PDF/A-Konformität.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Gibt den Zoom‑Wert in Prozent an. Standard ist 100.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Gibt den Zoom‑Wert in Prozent an. Standard ist 100.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLinearize() {#getLinearize--}
```
public final boolean getLinearize()
```


Linearisiert das PDF-Dokument für das Web.


**Returns:**
boolean
### setLinearize(boolean value) {#setLinearize-boolean-}
```
public final void setLinearize(boolean value)
```


Linearisiert das PDF-Dokument für das Web.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getOptimizationOptions() {#getOptimizationOptions--}
```
public final PdfOptimizationOptions getOptimizationOptions()
```


PDF-Optimierungsoptionen


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions)
### setOptimizationOptions(PdfOptimizationOptions value) {#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-}
```
public final void setOptimizationOptions(PdfOptimizationOptions value)
```


PDF-Optimierungsoptionen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Konvertiert ein PDF vom RGB-Farbraum in Graustufen


**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Konvertiert ein PDF vom RGB-Farbraum in Graustufen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public final PdfFormattingOptions getFormattingOptions()
```


PDF-Formatierungsoptionen


**Returns:**
[PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions)
### setFormattingOptions(PdfFormattingOptions value) {#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-}
```
public final void setFormattingOptions(PdfFormattingOptions value)
```


PDF-Formatierungsoptionen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public PdfDocumentInfo getDocumentInfo()
```


Metainformationen des PDF-Dokuments.


**Returns:**
[PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo)
### setDocumentInfo(PdfDocumentInfo documentInfo) {#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-}
```
public void setDocumentInfo(PdfDocumentInfo documentInfo)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| documentInfo | [PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo) |  |

