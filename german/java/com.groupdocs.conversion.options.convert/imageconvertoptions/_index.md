---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen für die Konvertierung zum Bilddateityp."
type: docs
weight: 18
url: /de/java/com.groupdocs.conversion.options.convert/imageconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageConvertOptions extends CommonConvertOptions<ImageFileType> implements Serializable
```

Optionen für die Konvertierung zum Bilddateityp.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ImageConvertOptions()](#ImageConvertOptions--) | Initialisiert eine neue Instanz der Klasse [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions). |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DEFAULT_DPI](#DEFAULT-DPI) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWidth()](#getWidth--) | Gewünschte Bildbreite nach der Konvertierung. |
|
|  | [setWidth(int value)](#setWidth-int-) | Gewünschte Bildbreite nach der Konvertierung. |
|
|  | [getHeight()](#getHeight--) | Gewünschte Bildhöhe nach der Konvertierung. |
|
|  | [setHeight(int value)](#setHeight-int-) | Gewünschte Bildhöhe nach der Konvertierung. |
|
|  | [getUsePdf()](#getUsePdf--) | Wenn |
true
, wird die Eingabe zunächst in PDF konvertiert und anschließend in das gewünschte Format.
|
|  | [setUsePdf(boolean value)](#setUsePdf-boolean-) | Wenn |
true
, wird die Eingabe zunächst in PDF konvertiert und anschließend in das gewünschte Format.
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Gewünschte horizontale Bildauflösung nach der Konvertierung. |
|
|  | [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Gewünschte horizontale Bildauflösung nach der Konvertierung. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Gewünschte vertikale Bildauflösung nach der Konvertierung. |
|
|  | [setVerticalResolution(int value)](#setVerticalResolution-int-) | Gewünschte vertikale Bildauflösung nach der Konvertierung. |
|
|  | [getTiffOptions()](#getTiffOptions--) | Tiff-spezifische Konvertierungsoptionen. |
|
|  | [setTiffOptions(TiffOptions value)](#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-) | Tiff-spezifische Konvertierungsoptionen. |
|
|  | [getPsdOptions()](#getPsdOptions--) | Psd-spezifische Konvertierungsoptionen. |
|
|  | [setPsdOptions(PsdOptions value)](#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-) | Psd-spezifische Konvertierungsoptionen. |
|
|  | [getWebpOptions()](#getWebpOptions--) | Webp-spezifische Konvertierungsoptionen. |
|
|  | [setWebpOptions(WebpOptions value)](#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-) | Webp-spezifische Konvertierungsoptionen. |
|
|  | [getGrayscale()](#getGrayscale--) | Gibt an, ob in ein Graustufenbild konvertiert werden soll. |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | Gibt an, ob in ein Graustufenbild konvertiert werden soll. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Bilddrehwinkel. |
|
|  | [setRotateAngle(int value)](#setRotateAngle-int-) | Bilddrehwinkel. |
|
|  | [getJpegOptions()](#getJpegOptions--) | Jpeg-spezifische Konvertierungsoptionen. |
|
|  | [setJpegOptions(JpegOptions value)](#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-) | Jpeg-spezifische Konvertierungsoptionen. |
|
|  | [getFlipMode()](#getFlipMode--) | Bildspiegelungsmodus. |
|
|  | [setFlipMode(ImageFlipModes value)](#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-) | Bildspiegelungsmodus. |
|
|  | [getBrightness()](#getBrightness--) | Passt die Bildhelligkeit an. |
|
|  | [setBrightness(int value)](#setBrightness-int-) | Passt die Bildhelligkeit an. |
|
|  | [getContrast()](#getContrast--) | Passt den Bildkontrast an. |
|
|  | [setContrast(int value)](#setContrast-int-) | Passt den Bildkontrast an. |
|
|  | [getGamma()](#getGamma--) | Passt die Bild-Gamma an. |
|
|  | [setGamma(float value)](#setGamma-float-) | Passt die Bild-Gamma an. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Ermittelt die Hintergrundfarbe |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Setzt die Hintergrundfarbe, sofern vom Quellformat unterstützt |
|
### ImageConvertOptions() {#ImageConvertOptions--}
```
public ImageConvertOptions()
```


Initialisiert eine neue Instanz der Klasse [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions).


### DEFAULT_DPI {#DEFAULT-DPI}
```
public static final int DEFAULT_DPI
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gewünschte Bildbreite nach der Konvertierung.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Gewünschte Bildbreite nach der Konvertierung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gewünschte Bildhöhe nach der Konvertierung.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Gewünschte Bildhöhe nach der Konvertierung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


Wenn
true
, wird die Eingabe zunächst in PDF konvertiert und anschließend in das gewünschte Format.


**Returns:**
boolean
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


Wenn
true
, wird die Eingabe zunächst in PDF konvertiert und anschließend in das gewünschte Format.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final int getHorizontalResolution()
```


Gewünschte horizontale Bildauflösung nach der Konvertierung. Die Standardauflösung ist die Auflösung der Eingabedatei oder 96 dpi.


**Returns:**
int
### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public final void setHorizontalResolution(int value)
```


Gewünschte horizontale Bildauflösung nach der Konvertierung. Die Standardauflösung ist die Auflösung der Eingabedatei oder 96 dpi.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final int getVerticalResolution()
```


Gewünschte vertikale Bildauflösung nach der Konvertierung. Die Standardauflösung ist die Auflösung der Eingabedatei oder 96 dpi.


**Returns:**
int
### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public final void setVerticalResolution(int value)
```


Gewünschte vertikale Bildauflösung nach der Konvertierung. Die Standardauflösung ist die Auflösung der Eingabedatei oder 96 dpi.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTiffOptions() {#getTiffOptions--}
```
public final TiffOptions getTiffOptions()
```


Tiff-spezifische Konvertierungsoptionen.


**Returns:**
[TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions)
### setTiffOptions(TiffOptions value) {#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-}
```
public final void setTiffOptions(TiffOptions value)
```


Tiff-spezifische Konvertierungsoptionen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions) |  |

### getPsdOptions() {#getPsdOptions--}
```
public final PsdOptions getPsdOptions()
```


Psd-spezifische Konvertierungsoptionen.


**Returns:**
[PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions)
### setPsdOptions(PsdOptions value) {#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-}
```
public final void setPsdOptions(PsdOptions value)
```


Psd-spezifische Konvertierungsoptionen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions) |  |

### getWebpOptions() {#getWebpOptions--}
```
public final WebpOptions getWebpOptions()
```


Webp-spezifische Konvertierungsoptionen.


**Returns:**
[WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions)
### setWebpOptions(WebpOptions value) {#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-}
```
public final void setWebpOptions(WebpOptions value)
```


Webp-spezifische Konvertierungsoptionen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Gibt an, ob in ein Graustufenbild konvertiert werden soll.


**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Gibt an, ob in ein Graustufenbild konvertiert werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getRotateAngle() {#getRotateAngle--}
```
public final int getRotateAngle()
```


Bilddrehwinkel.


**Returns:**
int
### setRotateAngle(int value) {#setRotateAngle-int-}
```
public final void setRotateAngle(int value)
```


Bilddrehwinkel.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Jpeg-spezifische Konvertierungsoptionen.


**Returns:**
[JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions)
### setJpegOptions(JpegOptions value) {#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Jpeg-spezifische Konvertierungsoptionen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) |  |

### getFlipMode() {#getFlipMode--}
```
public final ImageFlipModes getFlipMode()
```


Bildspiegelungsmodus.


**Returns:**
[ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes)
### setFlipMode(ImageFlipModes value) {#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-}
```
public final void setFlipMode(ImageFlipModes value)
```


Bildspiegelungsmodus.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes) |  |

### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Passt die Bildhelligkeit an.


**Returns:**
int
### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Passt die Bildhelligkeit an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getContrast() {#getContrast--}
```
public final int getContrast()
```


Passt den Bildkontrast an.


**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Passt den Bildkontrast an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getGamma() {#getGamma--}
```
public final float getGamma()
```


Passt die Bild-Gamma an.


**Returns:**
float
### setGamma(float value) {#setGamma-float-}
```
public final void setGamma(float value)
```


Passt die Bild-Gamma an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Ermittelt die Hintergrundfarbe


**Returns:**
com.aspose.ms.System.Drawing.Color - Hintergrundfarbe

### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Setzt die Hintergrundfarbe, sofern vom Quellformat unterstützt


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | backgroundColor | com.aspose.ms.System.Drawing.Color | Hintergrundfarbe |
|

