---
title: "ImageConvertOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options pour la conversion vers le type de fichier Image."
type: docs
weight: 18
url: /fr/java/com.groupdocs.conversion.options.convert/imageconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageConvertOptions extends CommonConvertOptions<ImageFileType> implements Serializable
```

Options pour la conversion vers le type de fichier Image.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [ImageConvertOptions()](#ImageConvertOptions--) | Initialise une nouvelle instance de la classe [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions). |
|
## Champs

| Champ | Description |
| --- | --- |
| [DEFAULT_DPI](#DEFAULT-DPI) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWidth()](#getWidth--) | Largeur d'image souhaitée après conversion. |
|
|  | [setWidth(int value)](#setWidth-int-) | Largeur d'image souhaitée après conversion. |
|
|  | [getHeight()](#getHeight--) | Hauteur d'image souhaitée après conversion. |
|
|  | [setHeight(int value)](#setHeight-int-) | Hauteur d'image souhaitée après conversion. |
|
|  | [getUsePdf()](#getUsePdf--) | Si |
true
, l'entrée est d'abord convertie en PDF puis au format souhaité.
|
|  | [setUsePdf(boolean value)](#setUsePdf-boolean-) | Si |
true
, l'entrée est d'abord convertie en PDF puis au format souhaité.
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Résolution horizontale de l'image souhaitée après conversion. |
|
|  | [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Résolution horizontale de l'image souhaitée après conversion. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Résolution verticale de l'image souhaitée après conversion. |
|
|  | [setVerticalResolution(int value)](#setVerticalResolution-int-) | Résolution verticale de l'image souhaitée après conversion. |
|
|  | [getTiffOptions()](#getTiffOptions--) | Options de conversion spécifiques à Tiff. |
|
|  | [setTiffOptions(TiffOptions value)](#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-) | Options de conversion spécifiques à Tiff. |
|
|  | [getPsdOptions()](#getPsdOptions--) | Options de conversion spécifiques à Psd. |
|
|  | [setPsdOptions(PsdOptions value)](#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-) | Options de conversion spécifiques à Psd. |
|
|  | [getWebpOptions()](#getWebpOptions--) | Options de conversion spécifiques à Webp. |
|
|  | [setWebpOptions(WebpOptions value)](#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-) | Options de conversion spécifiques à Webp. |
|
|  | [getGrayscale()](#getGrayscale--) | Indique s'il faut convertir en image en niveaux de gris. |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | Indique s'il faut convertir en image en niveaux de gris. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Angle de rotation de l'image. |
|
|  | [setRotateAngle(int value)](#setRotateAngle-int-) | Angle de rotation de l'image. |
|
|  | [getJpegOptions()](#getJpegOptions--) | Options de conversion spécifiques à Jpeg. |
|
|  | [setJpegOptions(JpegOptions value)](#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-) | Options de conversion spécifiques à Jpeg. |
|
|  | [getFlipMode()](#getFlipMode--) | Mode de retournement de l'image. |
|
|  | [setFlipMode(ImageFlipModes value)](#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-) | Mode de retournement de l'image. |
|
|  | [getBrightness()](#getBrightness--) | Ajuste la luminosité de l'image. |
|
|  | [setBrightness(int value)](#setBrightness-int-) | Ajuste la luminosité de l'image. |
|
|  | [getContrast()](#getContrast--) | Ajuste le contraste de l'image. |
|
|  | [setContrast(int value)](#setContrast-int-) | Ajuste le contraste de l'image. |
|
|  | [getGamma()](#getGamma--) | Ajuste le gamma de l'image. |
|
|  | [setGamma(float value)](#setGamma-float-) | Ajuste le gamma de l'image. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Obtient la couleur d'arrière-plan |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Définit la couleur d'arrière-plan lorsque le format source le prend en charge |
|
### ImageConvertOptions() {#ImageConvertOptions--}
```
public ImageConvertOptions()
```


Initialise une nouvelle instance de la classe [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions).


### DEFAULT_DPI {#DEFAULT-DPI}
```
public static final int DEFAULT_DPI
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Largeur d'image souhaitée après conversion.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Largeur d'image souhaitée après conversion.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hauteur d'image souhaitée après conversion.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Hauteur d'image souhaitée après conversion.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


Si
true
, l'entrée est d'abord convertie en PDF puis au format souhaité.


**Returns:**
booléen
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


Si
true
, l'entrée est d'abord convertie en PDF puis au format souhaité.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final int getHorizontalResolution()
```


Résolution horizontale de l'image souhaitée après conversion. La résolution par défaut est celle du fichier d'entrée ou 96 dpi.


**Returns:**
int
### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public final void setHorizontalResolution(int value)
```


Résolution horizontale de l'image souhaitée après conversion. La résolution par défaut est celle du fichier d'entrée ou 96 dpi.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final int getVerticalResolution()
```


Résolution verticale de l'image souhaitée après conversion. La résolution par défaut est celle du fichier d'entrée ou 96 dpi.


**Returns:**
int
### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public final void setVerticalResolution(int value)
```


Résolution verticale de l'image souhaitée après conversion. La résolution par défaut est celle du fichier d'entrée ou 96 dpi.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTiffOptions() {#getTiffOptions--}
```
public final TiffOptions getTiffOptions()
```


Options de conversion spécifiques à Tiff.


**Returns:**
[TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions)
### setTiffOptions(TiffOptions value) {#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-}
```
public final void setTiffOptions(TiffOptions value)
```


Options de conversion spécifiques à Tiff.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions) |  |

### getPsdOptions() {#getPsdOptions--}
```
public final PsdOptions getPsdOptions()
```


Options de conversion spécifiques à Psd.


**Returns:**
[PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions)
### setPsdOptions(PsdOptions value) {#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-}
```
public final void setPsdOptions(PsdOptions value)
```


Options de conversion spécifiques à Psd.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions) |  |

### getWebpOptions() {#getWebpOptions--}
```
public final WebpOptions getWebpOptions()
```


Options de conversion spécifiques à Webp.


**Returns:**
[WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions)
### setWebpOptions(WebpOptions value) {#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-}
```
public final void setWebpOptions(WebpOptions value)
```


Options de conversion spécifiques à Webp.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Indique s'il faut convertir en image en niveaux de gris.


**Returns:**
booléen
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Indique s'il faut convertir en image en niveaux de gris.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getRotateAngle() {#getRotateAngle--}
```
public final int getRotateAngle()
```


Angle de rotation de l'image.


**Returns:**
int
### setRotateAngle(int value) {#setRotateAngle-int-}
```
public final void setRotateAngle(int value)
```


Angle de rotation de l'image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Options de conversion spécifiques à Jpeg.


**Returns:**
[JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions)
### setJpegOptions(JpegOptions value) {#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Options de conversion spécifiques à Jpeg.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) |  |

### getFlipMode() {#getFlipMode--}
```
public final ImageFlipModes getFlipMode()
```


Mode de retournement de l'image.


**Returns:**
[ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes)
### setFlipMode(ImageFlipModes value) {#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-}
```
public final void setFlipMode(ImageFlipModes value)
```


Mode de retournement de l'image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes) |  |

### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Ajuste la luminosité de l'image.


**Returns:**
int
### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Ajuste la luminosité de l'image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getContrast() {#getContrast--}
```
public final int getContrast()
```


Ajuste le contraste de l'image.


**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Ajuste le contraste de l'image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getGamma() {#getGamma--}
```
public final float getGamma()
```


Ajuste le gamma de l'image.


**Returns:**
float
### setGamma(float value) {#setGamma-float-}
```
public final void setGamma(float value)
```


Ajuste le gamma de l'image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Obtient la couleur d'arrière-plan


**Returns:**
com.aspose.ms.System.Drawing.Color - couleur d'arrière-plan

### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Définit la couleur d'arrière-plan lorsque le format source le prend en charge


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | backgroundColor | com.aspose.ms.System.Drawing.Color | couleur d'arrière-plan |
|

