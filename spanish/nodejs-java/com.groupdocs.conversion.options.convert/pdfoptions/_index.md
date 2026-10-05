---
title: "PdfOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para la conversión al tipo de archivo Pdf."
type: docs
weight: 30
url: /es/nodejs-java/com.groupdocs.conversion.options.convert/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptions extends ValueObject implements Serializable
```

Opciones para la conversión al tipo de archivo Pdf.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | ctor |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPdfFormat()](#getPdfFormat--) | Establece el formato pdf del documento convertido. |
| [setPdfFormat(PdfFormats value)](#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-) | Establece el formato pdf del documento convertido. |
| [getRemovePdfACompliance()](#getRemovePdfACompliance--) | Elimina la conformidad Pdf-A |
| [setRemovePdfACompliance(boolean value)](#setRemovePdfACompliance-boolean-) | Elimina la conformidad Pdf-A |
| [getZoom()](#getZoom--) | Especifica el nivel de zoom en porcentaje. |
| [setZoom(int value)](#setZoom-int-) | Especifica el nivel de zoom en porcentaje. |
| [getLinearize()](#getLinearize--) | Linealiza el documento PDF para la web |
| [setLinearize(boolean value)](#setLinearize-boolean-) | Linealiza el documento PDF para la web |
| [getOptimizationOptions()](#getOptimizationOptions--) | Opciones de optimización de PDF |
| [setOptimizationOptions(PdfOptimizationOptions value)](#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-) | Opciones de optimización de PDF |
| [getGrayscale()](#getGrayscale--) | Convierte un PDF del espacio de color RGB a escala de grises |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Convierte un PDF del espacio de color RGB a escala de grises |
| [getFormattingOptions()](#getFormattingOptions--) | Opciones de formato de PDF |
| [setFormattingOptions(PdfFormattingOptions value)](#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-) | Opciones de formato de PDF |
| [getDocumentInfo()](#getDocumentInfo--) | Información meta del documento PDF. |
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


Establece el formato pdf del documento convertido.

**Returns:**
[PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats)
### setPdfFormat(PdfFormats value) {#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-}
```
public final void setPdfFormat(PdfFormats value)
```


Establece el formato pdf del documento convertido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats) |  |

### getRemovePdfACompliance() {#getRemovePdfACompliance--}
```
public final boolean getRemovePdfACompliance()
```


Elimina la conformidad Pdf-A

**Returns:**
boolean
### setRemovePdfACompliance(boolean value) {#setRemovePdfACompliance-boolean-}
```
public final void setRemovePdfACompliance(boolean value)
```


Elimina la conformidad Pdf-A

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Especifica el nivel de zoom en porcentaje. El valor predeterminado es 100.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Especifica el nivel de zoom en porcentaje. El valor predeterminado es 100.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLinearize() {#getLinearize--}
```
public final boolean getLinearize()
```


Linealiza el documento PDF para la web

**Returns:**
boolean
### setLinearize(boolean value) {#setLinearize-boolean-}
```
public final void setLinearize(boolean value)
```


Linealiza el documento PDF para la web

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getOptimizationOptions() {#getOptimizationOptions--}
```
public final PdfOptimizationOptions getOptimizationOptions()
```


Opciones de optimización de PDF

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions)
### setOptimizationOptions(PdfOptimizationOptions value) {#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-}
```
public final void setOptimizationOptions(PdfOptimizationOptions value)
```


Opciones de optimización de PDF

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Convierte un PDF del espacio de color RGB a escala de grises

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Convierte un PDF del espacio de color RGB a escala de grises

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public final PdfFormattingOptions getFormattingOptions()
```


Opciones de formato de PDF

**Returns:**
[PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions)
### setFormattingOptions(PdfFormattingOptions value) {#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-}
```
public final void setFormattingOptions(PdfFormattingOptions value)
```


Opciones de formato de PDF

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public PdfDocumentInfo getDocumentInfo()
```


Información meta del documento PDF.

**Returns:**
[PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo)
### setDocumentInfo(PdfDocumentInfo documentInfo) {#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-}
```
public void setDocumentInfo(PdfDocumentInfo documentInfo)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documentInfo | [PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo) |  |

