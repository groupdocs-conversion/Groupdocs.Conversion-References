---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor conversie naar Image-bestandstype."
type: docs
weight: 18
url: /nl/java/com.groupdocs.conversion.options.convert/imageconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageConvertOptions extends CommonConvertOptions<ImageFileType> implements Serializable
```

Opties voor conversie naar Image-bestandstype.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ImageConvertOptions()](#ImageConvertOptions--) | Initialiseert een nieuw exemplaar van de klasse [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions). |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
| [DEFAULT_DPI](#DEFAULT-DPI) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWidth()](#getWidth--) | Gewenste afbeeldingsbreedte na conversie. |
|
|  | [setWidth(int value)](#setWidth-int-) | Gewenste afbeeldingsbreedte na conversie. |
|
|  | [getHeight()](#getHeight--) | Gewenste afbeeldingshoogte na conversie. |
|
|  | [setHeight(int value)](#setHeight-int-) | Gewenste afbeeldingshoogte na conversie. |
|
|  | [getUsePdf()](#getUsePdf--) | Als |
true
, wordt de invoer eerst naar PDF geconverteerd en daarna naar het gewenste formaat.
|
|  | [setUsePdf(boolean value)](#setUsePdf-boolean-) | Als |
true
, wordt de invoer eerst naar PDF geconverteerd en daarna naar het gewenste formaat.
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Gewenste horizontale resolutie van de afbeelding na conversie. |
|
|  | [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Gewenste horizontale resolutie van de afbeelding na conversie. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Gewenste verticale resolutie van de afbeelding na conversie. |
|
|  | [setVerticalResolution(int value)](#setVerticalResolution-int-) | Gewenste verticale resolutie van de afbeelding na conversie. |
|
|  | [getTiffOptions()](#getTiffOptions--) | Tiff-specifieke conversie-opties. |
|
|  | [setTiffOptions(TiffOptions value)](#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-) | Tiff-specifieke conversie-opties. |
|
|  | [getPsdOptions()](#getPsdOptions--) | Psd-specifieke conversie-opties. |
|
|  | [setPsdOptions(PsdOptions value)](#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-) | Psd-specifieke conversie-opties. |
|
|  | [getWebpOptions()](#getWebpOptions--) | Webp-specifieke conversie-opties. |
|
|  | [setWebpOptions(WebpOptions value)](#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-) | Webp-specifieke conversie-opties. |
|
|  | [getGrayscale()](#getGrayscale--) | Geeft aan of er moet worden geconverteerd naar een grijswaardenafbeelding. |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | Geeft aan of er moet worden geconverteerd naar een grijswaardenafbeelding. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Rotatiehoek van de afbeelding. |
|
|  | [setRotateAngle(int value)](#setRotateAngle-int-) | Rotatiehoek van de afbeelding. |
|
|  | [getJpegOptions()](#getJpegOptions--) | Jpeg-specifieke conversie-opties. |
|
|  | [setJpegOptions(JpegOptions value)](#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-) | Jpeg-specifieke conversie-opties. |
|
|  | [getFlipMode()](#getFlipMode--) | Spiegelmodus van de afbeelding. |
|
|  | [setFlipMode(ImageFlipModes value)](#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-) | Spiegelmodus van de afbeelding. |
|
|  | [getBrightness()](#getBrightness--) | Past de helderheid van de afbeelding aan. |
|
|  | [setBrightness(int value)](#setBrightness-int-) | Past de helderheid van de afbeelding aan. |
|
|  | [getContrast()](#getContrast--) | Past het contrast van de afbeelding aan. |
|
|  | [setContrast(int value)](#setContrast-int-) | Past het contrast van de afbeelding aan. |
|
|  | [getGamma()](#getGamma--) | Past de gamma van de afbeelding aan. |
|
|  | [setGamma(float value)](#setGamma-float-) | Past de gamma van de afbeelding aan. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Haalt achtergrondkleur op |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Stelt de achtergrondkleur in waar dit wordt ondersteund door het bronformaat |
|
### ImageConvertOptions() {#ImageConvertOptions--}
```
public ImageConvertOptions()
```


Initialiseert een nieuw exemplaar van de klasse [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions).


### DEFAULT_DPI {#DEFAULT-DPI}
```
public static final int DEFAULT_DPI
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gewenste afbeeldingsbreedte na conversie.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Gewenste afbeeldingsbreedte na conversie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gewenste afbeeldingshoogte na conversie.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Gewenste afbeeldingshoogte na conversie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


Als
true
, wordt de invoer eerst naar PDF geconverteerd en daarna naar het gewenste formaat.


**Returns:**
boolean
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


Als
true
, wordt de invoer eerst naar PDF geconverteerd en daarna naar het gewenste formaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final int getHorizontalResolution()
```


Gewenste horizontale resolutie van de afbeelding na conversie. De standaardresolutie is de resolutie van het invoerbestand of 96 dpi.


**Returns:**
int
### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public final void setHorizontalResolution(int value)
```


Gewenste horizontale resolutie van de afbeelding na conversie. De standaardresolutie is de resolutie van het invoerbestand of 96 dpi.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final int getVerticalResolution()
```


Gewenste verticale resolutie van de afbeelding na conversie. De standaardresolutie is de resolutie van het invoerbestand of 96 dpi.


**Returns:**
int
### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public final void setVerticalResolution(int value)
```


Gewenste verticale resolutie van de afbeelding na conversie. De standaardresolutie is de resolutie van het invoerbestand of 96 dpi.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getTiffOptions() {#getTiffOptions--}
```
public final TiffOptions getTiffOptions()
```


Tiff-specifieke conversie-opties.


**Returns:**
[TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions)
### setTiffOptions(TiffOptions value) {#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-}
```
public final void setTiffOptions(TiffOptions value)
```


Tiff-specifieke conversie-opties.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions) |  |

### getPsdOptions() {#getPsdOptions--}
```
public final PsdOptions getPsdOptions()
```


Psd-specifieke conversie-opties.


**Returns:**
[PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions)
### setPsdOptions(PsdOptions value) {#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-}
```
public final void setPsdOptions(PsdOptions value)
```


Psd-specifieke conversie-opties.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions) |  |

### getWebpOptions() {#getWebpOptions--}
```
public final WebpOptions getWebpOptions()
```


Webp-specifieke conversie-opties.


**Returns:**
[WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions)
### setWebpOptions(WebpOptions value) {#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-}
```
public final void setWebpOptions(WebpOptions value)
```


Webp-specifieke conversie-opties.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Geeft aan of er moet worden geconverteerd naar een grijswaardenafbeelding.


**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Geeft aan of er moet worden geconverteerd naar een grijswaardenafbeelding.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getRotateAngle() {#getRotateAngle--}
```
public final int getRotateAngle()
```


Rotatiehoek van de afbeelding.


**Returns:**
int
### setRotateAngle(int value) {#setRotateAngle-int-}
```
public final void setRotateAngle(int value)
```


Rotatiehoek van de afbeelding.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Jpeg-specifieke conversie-opties.


**Returns:**
[JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions)
### setJpegOptions(JpegOptions value) {#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Jpeg-specifieke conversie-opties.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) |  |

### getFlipMode() {#getFlipMode--}
```
public final ImageFlipModes getFlipMode()
```


Spiegelmodus van de afbeelding.


**Returns:**
[ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes)
### setFlipMode(ImageFlipModes value) {#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-}
```
public final void setFlipMode(ImageFlipModes value)
```


Spiegelmodus van de afbeelding.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes) |  |

### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Past de helderheid van de afbeelding aan.


**Returns:**
int
### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Past de helderheid van de afbeelding aan.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getContrast() {#getContrast--}
```
public final int getContrast()
```


Past het contrast van de afbeelding aan.


**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Past het contrast van de afbeelding aan.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getGamma() {#getGamma--}
```
public final float getGamma()
```


Past de gamma van de afbeelding aan.


**Returns:**
float
### setGamma(float value) {#setGamma-float-}
```
public final void setGamma(float value)
```


Past de gamma van de afbeelding aan.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Haalt achtergrondkleur op


**Returns:**
com.aspose.ms.System.Drawing.Color - achtergrondkleur

### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Stelt de achtergrondkleur in waar dit wordt ondersteund door het bronformaat


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | backgroundColor | com.aspose.ms.System.Drawing.Color | achtergrondkleur |
|

