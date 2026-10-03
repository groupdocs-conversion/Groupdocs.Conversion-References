---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för konvertering till Bildfiltyp."
type: docs
weight: 18
url: /sv/java/com.groupdocs.conversion.options.convert/imageconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageConvertOptions extends CommonConvertOptions<ImageFileType> implements Serializable
```

Alternativ för konvertering till Bildfiltyp.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [ImageConvertOptions()](#ImageConvertOptions--) | Initierar en ny instans av [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions) klass. |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DEFAULT_DPI](#DEFAULT-DPI) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWidth()](#getWidth--) | Önskad bildbredd efter konvertering. |
|
|  | [setWidth(int value)](#setWidth-int-) | Önskad bildbredd efter konvertering. |
|
|  | [getHeight()](#getHeight--) | Önskad bildhöjd efter konvertering. |
|
|  | [setHeight(int value)](#setHeight-int-) | Önskad bildhöjd efter konvertering. |
|
|  | [getUsePdf()](#getUsePdf--) | Om |
true
, ingången konverteras först till PDF och därefter till önskat format.
|
|  | [setUsePdf(boolean value)](#setUsePdf-boolean-) | Om |
true
, ingången konverteras först till PDF och därefter till önskat format.
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Önskad horisontell upplösning för bilden efter konvertering. |
|
|  | [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Önskad horisontell upplösning för bilden efter konvertering. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Önskad vertikal upplösning för bilden efter konvertering. |
|
|  | [setVerticalResolution(int value)](#setVerticalResolution-int-) | Önskad vertikal upplösning för bilden efter konvertering. |
|
|  | [getTiffOptions()](#getTiffOptions--) | Tiff-specifika konverteringsalternativ. |
|
|  | [setTiffOptions(TiffOptions value)](#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-) | Tiff-specifika konverteringsalternativ. |
|
|  | [getPsdOptions()](#getPsdOptions--) | Psd-specifika konverteringsalternativ. |
|
|  | [setPsdOptions(PsdOptions value)](#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-) | Psd-specifika konverteringsalternativ. |
|
|  | [getWebpOptions()](#getWebpOptions--) | Webp-specifika konverteringsalternativ. |
|
|  | [setWebpOptions(WebpOptions value)](#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-) | Webp-specifika konverteringsalternativ. |
|
|  | [getGrayscale()](#getGrayscale--) | Anger om bilden ska konverteras till gråskala. |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | Anger om bilden ska konverteras till gråskala. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Bildrotationsvinkel. |
|
|  | [setRotateAngle(int value)](#setRotateAngle-int-) | Bildrotationsvinkel. |
|
|  | [getJpegOptions()](#getJpegOptions--) | Jpeg-specifika konverteringsalternativ. |
|
|  | [setJpegOptions(JpegOptions value)](#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-) | Jpeg-specifika konverteringsalternativ. |
|
|  | [getFlipMode()](#getFlipMode--) | Bildvändningsläge. |
|
|  | [setFlipMode(ImageFlipModes value)](#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-) | Bildvändningsläge. |
|
|  | [getBrightness()](#getBrightness--) | Justera bildens ljusstyrka. |
|
|  | [setBrightness(int value)](#setBrightness-int-) | Justera bildens ljusstyrka. |
|
|  | [getContrast()](#getContrast--) | Justera bildens kontrast. |
|
|  | [setContrast(int value)](#setContrast-int-) | Justera bildens kontrast. |
|
|  | [getGamma()](#getGamma--) | Justera bildens gamma. |
|
|  | [setGamma(float value)](#setGamma-float-) | Justera bildens gamma. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Hämtar bakgrundsfärg |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Ställer in bakgrundsfärg där det stöds av källformatet |
|
### ImageConvertOptions() {#ImageConvertOptions--}
```
public ImageConvertOptions()
```


Initierar en ny instans av [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions) klass.


### DEFAULT_DPI {#DEFAULT-DPI}
```
public static final int DEFAULT_DPI
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Önskad bildbredd efter konvertering.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Önskad bildbredd efter konvertering.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Önskad bildhöjd efter konvertering.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Önskad bildhöjd efter konvertering.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


Om
true
, ingången konverteras först till PDF och därefter till önskat format.


**Returns:**
boolean
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


Om
true
, ingången konverteras först till PDF och därefter till önskat format.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final int getHorizontalResolution()
```


Önskad horisontell upplösning för bilden efter konvertering. Standardupplösningen är upplösningen i indatafilen eller 96 dpi.


**Returns:**
int
### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public final void setHorizontalResolution(int value)
```


Önskad horisontell upplösning för bilden efter konvertering. Standardupplösningen är upplösningen i indatafilen eller 96 dpi.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final int getVerticalResolution()
```


Önskad vertikal bildupplösning efter konvertering. Standardupplösningen är upplösningen för indatafilen eller 96 dpi.


**Returns:**
int
### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public final void setVerticalResolution(int value)
```


Önskad vertikal bildupplösning efter konvertering. Standardupplösningen är upplösningen för indatafilen eller 96 dpi.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTiffOptions() {#getTiffOptions--}
```
public final TiffOptions getTiffOptions()
```


Tiff-specifika konverteringsalternativ.


**Returns:**
[TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions)
### setTiffOptions(TiffOptions value) {#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-}
```
public final void setTiffOptions(TiffOptions value)
```


Tiff-specifika konverteringsalternativ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions) |  |

### getPsdOptions() {#getPsdOptions--}
```
public final PsdOptions getPsdOptions()
```


Psd-specifika konverteringsalternativ.


**Returns:**
[PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions)
### setPsdOptions(PsdOptions value) {#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-}
```
public final void setPsdOptions(PsdOptions value)
```


Psd-specifika konverteringsalternativ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions) |  |

### getWebpOptions() {#getWebpOptions--}
```
public final WebpOptions getWebpOptions()
```


Webp-specifika konverteringsalternativ.


**Returns:**
[WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions)
### setWebpOptions(WebpOptions value) {#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-}
```
public final void setWebpOptions(WebpOptions value)
```


Webp-specifika konverteringsalternativ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Anger om bilden ska konverteras till gråskala.


**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Anger om bilden ska konverteras till gråskala.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getRotateAngle() {#getRotateAngle--}
```
public final int getRotateAngle()
```


Bildrotationsvinkel.


**Returns:**
int
### setRotateAngle(int value) {#setRotateAngle-int-}
```
public final void setRotateAngle(int value)
```


Bildrotationsvinkel.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Jpeg-specifika konverteringsalternativ.


**Returns:**
[JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions)
### setJpegOptions(JpegOptions value) {#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Jpeg-specifika konverteringsalternativ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) |  |

### getFlipMode() {#getFlipMode--}
```
public final ImageFlipModes getFlipMode()
```


Bildvändningsläge.


**Returns:**
[ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes)
### setFlipMode(ImageFlipModes value) {#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-}
```
public final void setFlipMode(ImageFlipModes value)
```


Bildvändningsläge.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes) |  |

### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Justera bildens ljusstyrka.


**Returns:**
int
### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Justera bildens ljusstyrka.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getContrast() {#getContrast--}
```
public final int getContrast()
```


Justera bildens kontrast.


**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Justera bildens kontrast.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getGamma() {#getGamma--}
```
public final float getGamma()
```


Justera bildens gamma.


**Returns:**
float
### setGamma(float value) {#setGamma-float-}
```
public final void setGamma(float value)
```


Justera bildens gamma.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Hämtar bakgrundsfärg


**Returns:**
com.aspose.ms.System.Drawing.Color - bakgrundsfärg

### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Ställer in bakgrundsfärg där det stöds av källformatet


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | backgroundColor | com.aspose.ms.System.Drawing.Color | bakgrundsfärg |
|

