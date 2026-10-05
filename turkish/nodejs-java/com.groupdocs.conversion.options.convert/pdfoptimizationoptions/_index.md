---
title: "PdfOptimizationOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Pdf optimizasyon seçeneklerini tanımlar."
type: docs
weight: 29
url: /tr/nodejs-java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptimizationOptions extends ValueObject implements Serializable
```

Pdf optimizasyon seçeneklerini tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Yeni bir [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | Yinelenen akışları bağla |
| [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | Yinelenen akışları bağla |
| [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | Kullanılmayan nesneleri kaldır |
| [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | Kullanılmayan nesneleri kaldır |
| [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | Kullanılmayan akışları kaldır |
| [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | Kullanılmayan akışları kaldır |
| [getCompressImages()](#getCompressImages--) | CompressImages true olarak ayarlanırsa, belgedeki tüm görüntüler yeniden sıkıştırılır. |
| [setCompressImages(boolean value)](#setCompressImages-boolean-) | CompressImages true olarak ayarlanırsa, belgedeki tüm görüntüler yeniden sıkıştırılır. |
| [getImageQuality()](#getImageQuality--) | Değer yüzde olarak, 100% değişmemiş kalite ve görüntü boyutudur. |
| [setImageQuality(int value)](#setImageQuality-int-) | Değer yüzde olarak, 100% değişmemiş kalite ve görüntü boyutudur. |
| [getUnembedFonts()](#getUnembedFonts--) | True olarak ayarlanırsa yazı tipleri gömülmez. |
| [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | True olarak ayarlanırsa yazı tipleri gömülmez. |
| [getFontSubsetStrategy()](#getFontSubsetStrategy--) |  |
| [setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)](#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-) | Yazı tipi alt küme stratejisini ayarla |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Yeni bir [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) sınıfı örneği başlatır.

### getLinkDuplicateStreams() {#getLinkDuplicateStreams--}
```
public final boolean getLinkDuplicateStreams()
```


Yinelenen akışları bağla

**Returns:**
boolean
### setLinkDuplicateStreams(boolean value) {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```


Yinelenen akışları bağla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


Kullanılmayan nesneleri kaldır

**Returns:**
boolean
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


Kullanılmayan nesneleri kaldır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


Kullanılmayan akışları kaldır

**Returns:**
boolean
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


Kullanılmayan akışları kaldır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


CompressImages true olarak ayarlanırsa, belgedeki tüm görüntüler yeniden sıkıştırılır. Sıkıştırma, ImageQuality özelliğiyle tanımlanır.

**Returns:**
boolean
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


CompressImages true olarak ayarlanırsa, belgedeki tüm görüntüler yeniden sıkıştırılır. Sıkıştırma, ImageQuality özelliğiyle tanımlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Değer yüzde olarak, 100% değişmemiş kalite ve görüntü boyutudur. Görüntü boyutunu azaltmak için bu özelliği 100'ün altına ayarlayın.

**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Değer yüzde olarak, 100% değişmemiş kalite ve görüntü boyutudur. Görüntü boyutunu azaltmak için bu özelliği 100'ün altına ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


True olarak ayarlanırsa yazı tipleri gömülmez.

**Returns:**
boolean
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


True olarak ayarlanırsa yazı tipleri gömülmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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


Yazı tipi alt küme stratejisini ayarla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontSubsetStrategy | [PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy) |  |

