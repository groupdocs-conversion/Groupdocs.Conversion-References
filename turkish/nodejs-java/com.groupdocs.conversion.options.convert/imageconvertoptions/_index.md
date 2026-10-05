---
title: "ImageConvertOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Görüntü dosya türüne dönüştürme seçenekleri."
type: docs
weight: 18
url: /tr/nodejs-java/com.groupdocs.conversion.options.convert/imageconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageConvertOptions extends CommonConvertOptions<ImageFileType> implements Serializable
```

Görüntü dosya türüne dönüştürme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageConvertOptions()](#ImageConvertOptions--) | Yeni bir [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions) sınıfının örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DEFAULT_DPI](#DEFAULT-DPI) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWidth()](#getWidth--) | Dönüştürmeden sonraki istenen görüntü genişliği. |
| [setWidth(int value)](#setWidth-int-) | Dönüştürmeden sonraki istenen görüntü genişliği. |
| [getHeight()](#getHeight--) | Dönüştürmeden sonraki istenen görüntü yüksekliği. |
| [setHeight(int value)](#setHeight-int-) | Dönüştürmeden sonraki istenen görüntü yüksekliği. |
| [getUsePdf()](#getUsePdf--) | Eğer true ise, girdi önce PDF'ye, ardından istenen formata dönüştürülür. |
| [setUsePdf(boolean value)](#setUsePdf-boolean-) | Eğer true ise, girdi önce PDF'ye, ardından istenen formata dönüştürülür. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Dönüştürmeden sonraki istenen görüntü yatay çözünürlüğü. |
| [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Dönüştürmeden sonraki istenen görüntü yatay çözünürlüğü. |
| [getVerticalResolution()](#getVerticalResolution--) | Dönüştürmeden sonraki istenen görüntü dikey çözünürlüğü. |
| [setVerticalResolution(int value)](#setVerticalResolution-int-) | Dönüştürmeden sonraki istenen görüntü dikey çözünürlüğü. |
| [getTiffOptions()](#getTiffOptions--) | Tiff özel dönüştürme seçenekleri. |
| [setTiffOptions(TiffOptions value)](#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-) | Tiff özel dönüştürme seçenekleri. |
| [getPsdOptions()](#getPsdOptions--) | Psd özel dönüştürme seçenekleri. |
| [setPsdOptions(PsdOptions value)](#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-) | Psd özel dönüştürme seçenekleri. |
| [getWebpOptions()](#getWebpOptions--) | Webp özel dönüştürme seçenekleri. |
| [setWebpOptions(WebpOptions value)](#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-) | Webp özel dönüştürme seçenekleri. |
| [getGrayscale()](#getGrayscale--) | Gri tonlamalı görüntüye dönüştürülüp dönüştürülmeyeceğini gösterir. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Gri tonlamalı görüntüye dönüştürülüp dönüştürülmeyeceğini gösterir. |
| [getRotateAngle()](#getRotateAngle--) | Görüntü döndürme açısı. |
| [setRotateAngle(int value)](#setRotateAngle-int-) | Görüntü döndürme açısı. |
| [getJpegOptions()](#getJpegOptions--) | Jpeg özel dönüştürme seçenekleri. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-) | Jpeg özel dönüştürme seçenekleri. |
| [getFlipMode()](#getFlipMode--) | Görüntü çevirme modu. |
| [setFlipMode(ImageFlipModes value)](#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-) | Görüntü çevirme modu. |
| [getBrightness()](#getBrightness--) | Görüntü parlaklığını ayarlar. |
| [setBrightness(int value)](#setBrightness-int-) | Görüntü parlaklığını ayarlar. |
| [getContrast()](#getContrast--) | Görüntü kontrastını ayarlar. |
| [setContrast(int value)](#setContrast-int-) | Görüntü kontrastını ayarlar. |
| [getGamma()](#getGamma--) | Görüntü gamasını ayarlar. |
| [setGamma(double value)](#setGamma-double-) | Görüntü gamasını ayarlar. |
| [setGamma(float value)](#setGamma-float-) | Görüntü gamasını ayarlar. |
| [getBackgroundColor()](#getBackgroundColor--) | Arka plan rengini alır |
| [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Kaynak formatın desteklediği yerlerde arka plan rengini ayarlar |
### ImageConvertOptions() {#ImageConvertOptions--}
```
public ImageConvertOptions()
```


Yeni bir [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions) sınıfının örneğini başlatır.

### DEFAULT_DPI {#DEFAULT-DPI}
```
public static final int DEFAULT_DPI
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Dönüştürmeden sonraki istenen görüntü genişliği.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Dönüştürmeden sonraki istenen görüntü genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Dönüştürmeden sonraki istenen görüntü yüksekliği.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Dönüştürmeden sonraki istenen görüntü yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


Eğer true ise, girdi önce PDF'ye, ardından istenen formata dönüştürülür.

**Returns:**
boolean
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


Eğer true ise, girdi önce PDF'ye, ardından istenen formata dönüştürülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final int getHorizontalResolution()
```


Dönüştürmeden sonraki istenen görüntü yatay çözünürlüğü. Varsayılan çözünürlük, giriş dosyasının çözünürlüğü veya 96 dpi'dir.

**Returns:**
int
### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public final void setHorizontalResolution(int value)
```


Dönüştürmeden sonraki istenen görüntü yatay çözünürlüğü. Varsayılan çözünürlük, giriş dosyasının çözünürlüğü veya 96 dpi'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final int getVerticalResolution()
```


Dönüştürmeden sonraki istenen görüntü dikey çözünürlüğü. Varsayılan çözünürlük, giriş dosyasının çözünürlüğü veya 96 dpi'dir.

**Returns:**
int
### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public final void setVerticalResolution(int value)
```


Dönüştürmeden sonraki istenen görüntü dikey çözünürlüğü. Varsayılan çözünürlük, giriş dosyasının çözünürlüğü veya 96 dpi'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTiffOptions() {#getTiffOptions--}
```
public final TiffOptions getTiffOptions()
```


Tiff özel dönüştürme seçenekleri.

**Returns:**
[TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions)
### setTiffOptions(TiffOptions value) {#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-}
```
public final void setTiffOptions(TiffOptions value)
```


Tiff özel dönüştürme seçenekleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions) |  |

### getPsdOptions() {#getPsdOptions--}
```
public final PsdOptions getPsdOptions()
```


Psd özel dönüştürme seçenekleri.

**Returns:**
[PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions)
### setPsdOptions(PsdOptions value) {#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-}
```
public final void setPsdOptions(PsdOptions value)
```


Psd özel dönüştürme seçenekleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions) |  |

### getWebpOptions() {#getWebpOptions--}
```
public final WebpOptions getWebpOptions()
```


Webp özel dönüştürme seçenekleri.

**Returns:**
[WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions)
### setWebpOptions(WebpOptions value) {#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-}
```
public final void setWebpOptions(WebpOptions value)
```


Webp özel dönüştürme seçenekleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Gri tonlamalı görüntüye dönüştürülüp dönüştürülmeyeceğini gösterir.

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Gri tonlamalı görüntüye dönüştürülüp dönüştürülmeyeceğini gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getRotateAngle() {#getRotateAngle--}
```
public final int getRotateAngle()
```


Görüntü döndürme açısı.

**Returns:**
int
### setRotateAngle(int value) {#setRotateAngle-int-}
```
public final void setRotateAngle(int value)
```


Görüntü döndürme açısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Jpeg özel dönüştürme seçenekleri.

**Returns:**
[JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions)
### setJpegOptions(JpegOptions value) {#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Jpeg özel dönüştürme seçenekleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) |  |

### getFlipMode() {#getFlipMode--}
```
public final ImageFlipModes getFlipMode()
```


Görüntü çevirme modu.

**Returns:**
[ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes)
### setFlipMode(ImageFlipModes value) {#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-}
```
public final void setFlipMode(ImageFlipModes value)
```


Görüntü çevirme modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes) |  |

### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Görüntü parlaklığını ayarlar.

**Returns:**
int
### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Görüntü parlaklığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getContrast() {#getContrast--}
```
public final int getContrast()
```


Görüntü kontrastını ayarlar.

**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Görüntü kontrastını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getGamma() {#getGamma--}
```
public final double getGamma()
```


Görüntü gamasını ayarlar.

**Returns:**
double
### setGamma(double value) {#setGamma-double-}
```
public final void setGamma(double value)
```


Görüntü gamasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setGamma(float value) {#setGamma-float-}
```
public final void setGamma(float value)
```


Görüntü gamasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Arka plan rengini alır

**Returns:**
com.aspose.ms.System.Drawing.Color - arka plan rengi
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Kaynak formatın desteklediği yerlerde arka plan rengini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color | arka plan rengi |

