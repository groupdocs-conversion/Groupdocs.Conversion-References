---
title: PdfOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for conversion to Pdf file type.
type: docs
weight: 30
url: /java/com.groupdocs.conversion.options.convert/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptions extends ValueObject implements Serializable
```

Options for conversion to Pdf file type.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | ctor |
## Methods

| Method | Description |
| --- | --- |
| [getPdfFormat()](#getPdfFormat--) | Sets the pdf format of the converted document. |
| [setPdfFormat(PdfFormats value)](#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-) | Sets the pdf format of the converted document. |
| [getRemovePdfACompliance()](#getRemovePdfACompliance--) | Removes Pdf-A Compliance |
| [setRemovePdfACompliance(boolean value)](#setRemovePdfACompliance-boolean-) | Removes Pdf-A Compliance |
| [getZoom()](#getZoom--) | Specifies the zoom level in percentage. |
| [setZoom(int value)](#setZoom-int-) | Specifies the zoom level in percentage. |
| [getLinearize()](#getLinearize--) | Linearizes PDF Document for the Web |
| [setLinearize(boolean value)](#setLinearize-boolean-) | Linearizes PDF Document for the Web |
| [getOptimizationOptions()](#getOptimizationOptions--) | Pdf optimization options |
| [setOptimizationOptions(PdfOptimizationOptions value)](#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-) | Pdf optimization options |
| [getGrayscale()](#getGrayscale--) | Convert a PDF from RGB colorspace to grayscale |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Convert a PDF from RGB colorspace to grayscale |
| [getFormattingOptions()](#getFormattingOptions--) | Pdf formatting options |
| [setFormattingOptions(PdfFormattingOptions value)](#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-) | Pdf formatting options |
| [getDocumentInfo()](#getDocumentInfo--) | Meta information of PDF document. |
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


Sets the pdf format of the converted document.

**Returns:**
[PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats)
### setPdfFormat(PdfFormats value) {#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-}
```
public final void setPdfFormat(PdfFormats value)
```


Sets the pdf format of the converted document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats) |  |

### getRemovePdfACompliance() {#getRemovePdfACompliance--}
```
public final boolean getRemovePdfACompliance()
```


Removes Pdf-A Compliance

**Returns:**
boolean
### setRemovePdfACompliance(boolean value) {#setRemovePdfACompliance-boolean-}
```
public final void setRemovePdfACompliance(boolean value)
```


Removes Pdf-A Compliance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Specifies the zoom level in percentage. Default is 100.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Specifies the zoom level in percentage. Default is 100.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLinearize() {#getLinearize--}
```
public final boolean getLinearize()
```


Linearizes PDF Document for the Web

**Returns:**
boolean
### setLinearize(boolean value) {#setLinearize-boolean-}
```
public final void setLinearize(boolean value)
```


Linearizes PDF Document for the Web

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOptimizationOptions() {#getOptimizationOptions--}
```
public final PdfOptimizationOptions getOptimizationOptions()
```


Pdf optimization options

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions)
### setOptimizationOptions(PdfOptimizationOptions value) {#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-}
```
public final void setOptimizationOptions(PdfOptimizationOptions value)
```


Pdf optimization options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Convert a PDF from RGB colorspace to grayscale

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Convert a PDF from RGB colorspace to grayscale

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public final PdfFormattingOptions getFormattingOptions()
```


Pdf formatting options

**Returns:**
[PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions)
### setFormattingOptions(PdfFormattingOptions value) {#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-}
```
public final void setFormattingOptions(PdfFormattingOptions value)
```


Pdf formatting options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public PdfDocumentInfo getDocumentInfo()
```


Meta information of PDF document.

**Returns:**
[PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo)
### setDocumentInfo(PdfDocumentInfo documentInfo) {#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-}
```
public void setDocumentInfo(PdfDocumentInfo documentInfo)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentInfo | [PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo) |  |

