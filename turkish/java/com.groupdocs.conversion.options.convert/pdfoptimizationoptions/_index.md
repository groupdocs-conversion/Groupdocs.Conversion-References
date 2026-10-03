---
title: "PdfOptimizationOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Pdf optimizasyon seçeneklerini tanımlar."
type: docs
weight: 29
url: /tr/java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
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
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Yeni bir [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) sınıf örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | Yinelenen akışları bağla |
|
|  | [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | Yinelenen akışları bağla |
|
|  | [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | Kullanılmayan nesneleri kaldır |
|
|  | [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | Kullanılmayan nesneleri kaldır |
|
|  | [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | Kullanılmayan akışları kaldır |
|
|  | [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | Kullanılmayan akışları kaldır |
|
|  | [getCompressImages()](#getCompressImages--) | Eğer CompressImages ayarlanırsa |
true
, belgedeki tüm görüntüler yeniden sıkıştırılır.
|
|  | [setCompressImages(boolean value)](#setCompressImages-boolean-) | Eğer CompressImages ayarlanırsa |
true
, belgedeki tüm görüntüler yeniden sıkıştırılır.
|
|  | [getImageQuality()](#getImageQuality--) | Yüzde cinsinden değer, %100'ün değişmemiş kalite ve görüntü boyutu olduğu durum. |
|
|  | [setImageQuality(int value)](#setImageQuality-int-) | Yüzde cinsinden değer, %100'ün değişmemiş kalite ve görüntü boyutu olduğu durum. |
|
|  | [getUnembedFonts()](#getUnembedFonts--) | True olarak ayarlanırsa yazı tiplerini gömülü olmaktan çıkar. |
|
|  | [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | True olarak ayarlanırsa yazı tiplerini gömülü olmaktan çıkar. |
|
| [getFontSubsetStrategy()](#getFontSubsetStrategy--) |  |
|  | [setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)](#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-) | Yazı tipi alt küme stratejisini ayarla |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Yeni bir [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) sınıf örneği başlatır.


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


Eğer CompressImages ayarlanırsa
true
, belgedeki tüm görüntüler yeniden sıkıştırılır. Sıkıştırma, ImageQuality özelliği tarafından tanımlanır.


**Returns:**
boolean
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


Eğer CompressImages ayarlanırsa
true
, belgedeki tüm görüntüler yeniden sıkıştırılır. Sıkıştırma, ImageQuality özelliği tarafından tanımlanır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Yüzde cinsinden değer, %100'ün değişmemiş kalite ve görüntü boyutu olduğu durum. Görüntü boyutunu azaltmak için bu özelliği 100'den düşük bir değere ayarlayın.


**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Yüzde cinsinden değer, %100'ün değişmemiş kalite ve görüntü boyutu olduğu durum. Görüntü boyutunu azaltmak için bu özelliği 100'den düşük bir değere ayarlayın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


True olarak ayarlanırsa yazı tiplerini gömülü olmaktan çıkar.


**Returns:**
boolean
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


True olarak ayarlanırsa yazı tiplerini gömülü olmaktan çıkar.


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

