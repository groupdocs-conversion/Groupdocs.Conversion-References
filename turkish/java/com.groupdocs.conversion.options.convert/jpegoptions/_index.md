---
title: "JpegOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Jpeg dosya türüne dönüştürme seçenekleri."
type: docs
weight: 20
url: /tr/java/com.groupdocs.conversion.options.convert/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class JpegOptions extends ValueObject implements Serializable
```

Jpeg dosya türüne dönüştürme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [JpegOptions()](#JpegOptions--) | Yeni bir [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) sınıfı örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getQuality()](#getQuality--) | İstenen görüntü kalitesi. |
|
|  | [setQuality(int value)](#setQuality-int-) | İstenen görüntü kalitesi. |
|
|  | [getColorMode()](#getColorMode--) | Jpg renk modu. |
|
|  | [setColorMode(JpgColorModes value)](#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-) | Jpg renk modu. |
|
|  | [getCompression()](#getCompression--) | Jpg sıkıştırma yöntemi. |
|
|  | [setCompression(JpgCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-) | Jpg sıkıştırma yöntemi. |
|
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Yeni bir [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) sınıfı örneğini başlatır.


### getQuality() {#getQuality--}
```
public final int getQuality()
```


İstenen görüntü kalitesi. Değer 0 ile 100 arasında olmalıdır. Varsayılan değer 100'dür.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public final void setQuality(int value)
```


İstenen görüntü kalitesi. Değer 0 ile 100 arasında olmalıdır. Varsayılan değer 100'dür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getColorMode() {#getColorMode--}
```
public final JpgColorModes getColorMode()
```


Jpg renk modu.


**Returns:**
[JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes)
### setColorMode(JpgColorModes value) {#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-}
```
public final void setColorMode(JpgColorModes value)
```


Jpg renk modu.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes) |  |

### getCompression() {#getCompression--}
```
public final JpgCompressionMethods getCompression()
```


Jpg sıkıştırma yöntemi.


**Returns:**
[JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods)
### setCompression(JpgCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-}
```
public final void setCompression(JpgCompressionMethods value)
```


Jpg sıkıştırma yöntemi.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods) |  |

