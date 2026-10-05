---
title: "PdfOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Pdf dosya türüne dönüştürme seçenekleri."
type: docs
weight: 30
url: /tr/nodejs-java/com.groupdocs.conversion.options.convert/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptions extends ValueObject implements Serializable
```

Pdf dosya türüne dönüştürme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | ctor |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPdfFormat()](#getPdfFormat--) | Dönüştürülen belgenin pdf formatını ayarlar. |
| [setPdfFormat(PdfFormats value)](#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-) | Dönüştürülen belgenin pdf formatını ayarlar. |
| [getRemovePdfACompliance()](#getRemovePdfACompliance--) | Pdf-A Uyumluluğunu kaldırır. |
| [setRemovePdfACompliance(boolean value)](#setRemovePdfACompliance-boolean-) | Pdf-A Uyumluluğunu kaldırır. |
| [getZoom()](#getZoom--) | Yakınlaştırma seviyesini yüzde olarak belirtir. |
| [setZoom(int value)](#setZoom-int-) | Yakınlaştırma seviyesini yüzde olarak belirtir. |
| [getLinearize()](#getLinearize--) | Web için PDF belgesini lineerleştirir. |
| [setLinearize(boolean value)](#setLinearize-boolean-) | Web için PDF belgesini lineerleştirir. |
| [getOptimizationOptions()](#getOptimizationOptions--) | Pdf optimizasyon seçenekleri |
| [setOptimizationOptions(PdfOptimizationOptions value)](#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-) | Pdf optimizasyon seçenekleri |
| [getGrayscale()](#getGrayscale--) | Bir PDF'i RGB renk uzayından gri tonlamaya dönüştürür |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Bir PDF'i RGB renk uzayından gri tonlamaya dönüştürür |
| [getFormattingOptions()](#getFormattingOptions--) | Pdf biçimlendirme seçenekleri |
| [setFormattingOptions(PdfFormattingOptions value)](#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-) | Pdf biçimlendirme seçenekleri |
| [getDocumentInfo()](#getDocumentInfo--) | PDF belgesinin meta bilgileri. |
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


Dönüştürülen belgenin pdf formatını ayarlar.

**Returns:**
[PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats)
### setPdfFormat(PdfFormats value) {#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-}
```
public final void setPdfFormat(PdfFormats value)
```


Dönüştürülen belgenin pdf formatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats) |  |

### getRemovePdfACompliance() {#getRemovePdfACompliance--}
```
public final boolean getRemovePdfACompliance()
```


Pdf-A Uyumluluğunu kaldırır.

**Returns:**
boolean
### setRemovePdfACompliance(boolean value) {#setRemovePdfACompliance-boolean-}
```
public final void setRemovePdfACompliance(boolean value)
```


Pdf-A Uyumluluğunu kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Yakınlaştırma seviyesini yüzde olarak belirtir. Varsayılan değer 100'dür.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Yakınlaştırma seviyesini yüzde olarak belirtir. Varsayılan değer 100'dür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLinearize() {#getLinearize--}
```
public final boolean getLinearize()
```


Web için PDF belgesini lineerleştirir.

**Returns:**
boolean
### setLinearize(boolean value) {#setLinearize-boolean-}
```
public final void setLinearize(boolean value)
```


Web için PDF belgesini lineerleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getOptimizationOptions() {#getOptimizationOptions--}
```
public final PdfOptimizationOptions getOptimizationOptions()
```


Pdf optimizasyon seçenekleri

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions)
### setOptimizationOptions(PdfOptimizationOptions value) {#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-}
```
public final void setOptimizationOptions(PdfOptimizationOptions value)
```


Pdf optimizasyon seçenekleri

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Bir PDF'i RGB renk uzayından gri tonlamaya dönüştürür

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Bir PDF'i RGB renk uzayından gri tonlamaya dönüştürür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public final PdfFormattingOptions getFormattingOptions()
```


Pdf biçimlendirme seçenekleri

**Returns:**
[PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions)
### setFormattingOptions(PdfFormattingOptions value) {#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-}
```
public final void setFormattingOptions(PdfFormattingOptions value)
```


Pdf biçimlendirme seçenekleri

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public PdfDocumentInfo getDocumentInfo()
```


PDF belgesinin meta bilgileri.

**Returns:**
[PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo)
### setDocumentInfo(PdfDocumentInfo documentInfo) {#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-}
```
public void setDocumentInfo(PdfDocumentInfo documentInfo)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| documentInfo | [PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo) |  |

