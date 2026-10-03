---
title: "PdfOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk konversi ke tipe file Pdf."
type: docs
weight: 30
url: /id/java/com.groupdocs.conversion.options.convert/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptions extends ValueObject implements Serializable
```

Opsi untuk konversi ke tipe file Pdf.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | ctor |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPdfFormat()](#getPdfFormat--) | Mengatur format pdf dari dokumen yang dikonversi. |
|
|  | [setPdfFormat(PdfFormats value)](#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-) | Mengatur format pdf dari dokumen yang dikonversi. |
|
|  | [getRemovePdfACompliance()](#getRemovePdfACompliance--) | Menghapus Kepatuhan Pdf-A |
|
|  | [setRemovePdfACompliance(boolean value)](#setRemovePdfACompliance-boolean-) | Menghapus Kepatuhan Pdf-A |
|
|  | [getZoom()](#getZoom--) | Menentukan tingkat zoom dalam persentase. |
|
|  | [setZoom(int value)](#setZoom-int-) | Menentukan tingkat zoom dalam persentase. |
|
|  | [getLinearize()](#getLinearize--) | Melinierkan Dokumen PDF untuk Web |
|
|  | [setLinearize(boolean value)](#setLinearize-boolean-) | Melinierkan Dokumen PDF untuk Web |
|
|  | [getOptimizationOptions()](#getOptimizationOptions--) | Opsi optimasi PDF |
|
|  | [setOptimizationOptions(PdfOptimizationOptions value)](#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-) | Opsi optimasi PDF |
|
|  | [getGrayscale()](#getGrayscale--) | Mengonversi PDF dari ruang warna RGB ke skala abu-abu |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | Mengonversi PDF dari ruang warna RGB ke skala abu-abu |
|
|  | [getFormattingOptions()](#getFormattingOptions--) | Opsi pemformatan PDF |
|
|  | [setFormattingOptions(PdfFormattingOptions value)](#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-) | Opsi pemformatan PDF |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Informasi meta dari dokumen PDF. |
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


Mengatur format pdf dari dokumen yang dikonversi.


**Returns:**
[PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats)
### setPdfFormat(PdfFormats value) {#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-}
```
public final void setPdfFormat(PdfFormats value)
```


Mengatur format pdf dari dokumen yang dikonversi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats) |  |

### getRemovePdfACompliance() {#getRemovePdfACompliance--}
```
public final boolean getRemovePdfACompliance()
```


Menghapus Kepatuhan Pdf-A


**Returns:**
boolean
### setRemovePdfACompliance(boolean value) {#setRemovePdfACompliance-boolean-}
```
public final void setRemovePdfACompliance(boolean value)
```


Menghapus Kepatuhan Pdf-A


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Menentukan tingkat zoom dalam persentase. Defaultnya adalah 100.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Menentukan tingkat zoom dalam persentase. Defaultnya adalah 100.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getLinearize() {#getLinearize--}
```
public final boolean getLinearize()
```


Melinierkan Dokumen PDF untuk Web


**Returns:**
boolean
### setLinearize(boolean value) {#setLinearize-boolean-}
```
public final void setLinearize(boolean value)
```


Melinierkan Dokumen PDF untuk Web


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getOptimizationOptions() {#getOptimizationOptions--}
```
public final PdfOptimizationOptions getOptimizationOptions()
```


Opsi optimasi PDF


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions)
### setOptimizationOptions(PdfOptimizationOptions value) {#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-}
```
public final void setOptimizationOptions(PdfOptimizationOptions value)
```


Opsi optimasi PDF


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Mengonversi PDF dari ruang warna RGB ke skala abu-abu


**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Mengonversi PDF dari ruang warna RGB ke skala abu-abu


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public final PdfFormattingOptions getFormattingOptions()
```


Opsi pemformatan PDF


**Returns:**
[PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions)
### setFormattingOptions(PdfFormattingOptions value) {#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-}
```
public final void setFormattingOptions(PdfFormattingOptions value)
```


Opsi pemformatan PDF


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public PdfDocumentInfo getDocumentInfo()
```


Informasi meta dari dokumen PDF.


**Returns:**
[PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo)
### setDocumentInfo(PdfDocumentInfo documentInfo) {#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-}
```
public void setDocumentInfo(PdfDocumentInfo documentInfo)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| documentInfo | [PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo) |  |

