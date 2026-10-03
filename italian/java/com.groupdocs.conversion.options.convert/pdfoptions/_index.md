---
title: "PdfOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per la conversione al tipo di file Pdf."
type: docs
weight: 30
url: /it/java/com.groupdocs.conversion.options.convert/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptions extends ValueObject implements Serializable
```

Opzioni per la conversione al tipo di file Pdf.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | ctor |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPdfFormat()](#getPdfFormat--) | Imposta il formato pdf del documento convertito. |
|
|  | [setPdfFormat(PdfFormats value)](#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-) | Imposta il formato pdf del documento convertito. |
|
|  | [getRemovePdfACompliance()](#getRemovePdfACompliance--) | Rimuove la conformità Pdf-A |
|
|  | [setRemovePdfACompliance(boolean value)](#setRemovePdfACompliance-boolean-) | Rimuove la conformità Pdf-A |
|
|  | [getZoom()](#getZoom--) | Specifica il livello di zoom in percentuale. |
|
|  | [setZoom(int value)](#setZoom-int-) | Specifica il livello di zoom in percentuale. |
|
|  | [getLinearize()](#getLinearize--) | Linearizza il documento PDF per il Web |
|
|  | [setLinearize(boolean value)](#setLinearize-boolean-) | Linearizza il documento PDF per il Web |
|
|  | [getOptimizationOptions()](#getOptimizationOptions--) | Opzioni di ottimizzazione PDF |
|
|  | [setOptimizationOptions(PdfOptimizationOptions value)](#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-) | Opzioni di ottimizzazione PDF |
|
|  | [getGrayscale()](#getGrayscale--) | Converti un PDF dallo spazio colore RGB a scala di grigi |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | Converti un PDF dallo spazio colore RGB a scala di grigi |
|
|  | [getFormattingOptions()](#getFormattingOptions--) | Opzioni di formattazione PDF |
|
|  | [setFormattingOptions(PdfFormattingOptions value)](#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-) | Opzioni di formattazione PDF |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Informazioni meta del documento PDF. |
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


Imposta il formato pdf del documento convertito.


**Returns:**
[PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats)
### setPdfFormat(PdfFormats value) {#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-}
```
public final void setPdfFormat(PdfFormats value)
```


Imposta il formato pdf del documento convertito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats) |  |

### getRemovePdfACompliance() {#getRemovePdfACompliance--}
```
public final boolean getRemovePdfACompliance()
```


Rimuove la conformità Pdf-A


**Returns:**
booleano
### setRemovePdfACompliance(boolean value) {#setRemovePdfACompliance-boolean-}
```
public final void setRemovePdfACompliance(boolean value)
```


Rimuove la conformità Pdf-A


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Specifica il livello di zoom in percentuale. Il valore predefinito è 100.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Specifica il livello di zoom in percentuale. Il valore predefinito è 100.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLinearize() {#getLinearize--}
```
public final boolean getLinearize()
```


Linearizza il documento PDF per il Web


**Returns:**
booleano
### setLinearize(boolean value) {#setLinearize-boolean-}
```
public final void setLinearize(boolean value)
```


Linearizza il documento PDF per il Web


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getOptimizationOptions() {#getOptimizationOptions--}
```
public final PdfOptimizationOptions getOptimizationOptions()
```


Opzioni di ottimizzazione PDF


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions)
### setOptimizationOptions(PdfOptimizationOptions value) {#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-}
```
public final void setOptimizationOptions(PdfOptimizationOptions value)
```


Opzioni di ottimizzazione PDF


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Converti un PDF dallo spazio colore RGB a scala di grigi


**Returns:**
booleano
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Converti un PDF dallo spazio colore RGB a scala di grigi


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public final PdfFormattingOptions getFormattingOptions()
```


Opzioni di formattazione PDF


**Returns:**
[PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions)
### setFormattingOptions(PdfFormattingOptions value) {#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-}
```
public final void setFormattingOptions(PdfFormattingOptions value)
```


Opzioni di formattazione PDF


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public PdfDocumentInfo getDocumentInfo()
```


Informazioni meta del documento PDF.


**Returns:**
[PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo)
### setDocumentInfo(PdfDocumentInfo documentInfo) {#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-}
```
public void setDocumentInfo(PdfDocumentInfo documentInfo)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentInfo | [PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo) |  |

