---
title: "ImageConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per la conversione al tipo di file Image."
type: docs
weight: 18
url: /it/java/com.groupdocs.conversion.options.convert/imageconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageConvertOptions extends CommonConvertOptions<ImageFileType> implements Serializable
```

Opzioni per la conversione al tipo di file Image.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ImageConvertOptions()](#ImageConvertOptions--) | Inizializza una nuova istanza della classe [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions). |
|
## Campi

| Campo | Descrizione |
| --- | --- |
| [DEFAULT_DPI](#DEFAULT-DPI) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWidth()](#getWidth--) | Larghezza desiderata dell'immagine dopo la conversione. |
|
|  | [setWidth(int value)](#setWidth-int-) | Larghezza desiderata dell'immagine dopo la conversione. |
|
|  | [getHeight()](#getHeight--) | Altezza desiderata dell'immagine dopo la conversione. |
|
|  | [setHeight(int value)](#setHeight-int-) | Altezza desiderata dell'immagine dopo la conversione. |
|
|  | [getUsePdf()](#getUsePdf--) | Se |
true
, l'input viene prima convertito in PDF e successivamente nel formato desiderato.
|
|  | [setUsePdf(boolean value)](#setUsePdf-boolean-) | Se |
true
, l'input viene prima convertito in PDF e successivamente nel formato desiderato.
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Risoluzione orizzontale desiderata dell'immagine dopo la conversione. |
|
|  | [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Risoluzione orizzontale desiderata dell'immagine dopo la conversione. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Risoluzione verticale desiderata dell'immagine dopo la conversione. |
|
|  | [setVerticalResolution(int value)](#setVerticalResolution-int-) | Risoluzione verticale desiderata dell'immagine dopo la conversione. |
|
|  | [getTiffOptions()](#getTiffOptions--) | Opzioni di conversione specifiche per Tiff. |
|
|  | [setTiffOptions(TiffOptions value)](#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-) | Opzioni di conversione specifiche per Tiff. |
|
|  | [getPsdOptions()](#getPsdOptions--) | Opzioni di conversione specifiche per Psd. |
|
|  | [setPsdOptions(PsdOptions value)](#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-) | Opzioni di conversione specifiche per Psd. |
|
|  | [getWebpOptions()](#getWebpOptions--) | Opzioni di conversione specifiche per Webp. |
|
|  | [setWebpOptions(WebpOptions value)](#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-) | Opzioni di conversione specifiche per Webp. |
|
|  | [getGrayscale()](#getGrayscale--) | Indica se convertire in un'immagine in scala di grigi. |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | Indica se convertire in un'immagine in scala di grigi. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Angolo di rotazione dell'immagine. |
|
|  | [setRotateAngle(int value)](#setRotateAngle-int-) | Angolo di rotazione dell'immagine. |
|
|  | [getJpegOptions()](#getJpegOptions--) | Opzioni di conversione specifiche per Jpeg. |
|
|  | [setJpegOptions(JpegOptions value)](#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-) | Opzioni di conversione specifiche per Jpeg. |
|
|  | [getFlipMode()](#getFlipMode--) | Modalità di ribaltamento dell'immagine. |
|
|  | [setFlipMode(ImageFlipModes value)](#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-) | Modalità di ribaltamento dell'immagine. |
|
|  | [getBrightness()](#getBrightness--) | Regola la luminosità dell'immagine. |
|
|  | [setBrightness(int value)](#setBrightness-int-) | Regola la luminosità dell'immagine. |
|
|  | [getContrast()](#getContrast--) | Regola il contrasto dell'immagine. |
|
|  | [setContrast(int value)](#setContrast-int-) | Regola il contrasto dell'immagine. |
|
|  | [getGamma()](#getGamma--) | Regola la gamma dell'immagine. |
|
|  | [setGamma(float value)](#setGamma-float-) | Regola la gamma dell'immagine. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Ottiene il colore di sfondo |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Imposta il colore di sfondo dove supportato dal formato di origine |
|
### ImageConvertOptions() {#ImageConvertOptions--}
```
public ImageConvertOptions()
```


Inizializza una nuova istanza della classe [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions).


### DEFAULT_DPI {#DEFAULT-DPI}
```
public static final int DEFAULT_DPI
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Larghezza desiderata dell'immagine dopo la conversione.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Larghezza desiderata dell'immagine dopo la conversione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Altezza desiderata dell'immagine dopo la conversione.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Altezza desiderata dell'immagine dopo la conversione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


Se
true
, l'input viene prima convertito in PDF e successivamente nel formato desiderato.


**Returns:**
booleano
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


Se
true
, l'input viene prima convertito in PDF e successivamente nel formato desiderato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final int getHorizontalResolution()
```


Risoluzione orizzontale desiderata dell'immagine dopo la conversione. La risoluzione predefinita è quella del file di input o 96 dpi.


**Returns:**
int
### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public final void setHorizontalResolution(int value)
```


Risoluzione orizzontale desiderata dell'immagine dopo la conversione. La risoluzione predefinita è quella del file di input o 96 dpi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final int getVerticalResolution()
```


Risoluzione verticale desiderata dell'immagine dopo la conversione. La risoluzione predefinita è quella del file di input o 96 dpi.


**Returns:**
int
### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public final void setVerticalResolution(int value)
```


Risoluzione verticale desiderata dell'immagine dopo la conversione. La risoluzione predefinita è quella del file di input o 96 dpi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTiffOptions() {#getTiffOptions--}
```
public final TiffOptions getTiffOptions()
```


Opzioni di conversione specifiche per Tiff.


**Returns:**
[TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions)
### setTiffOptions(TiffOptions value) {#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-}
```
public final void setTiffOptions(TiffOptions value)
```


Opzioni di conversione specifiche per Tiff.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions) |  |

### getPsdOptions() {#getPsdOptions--}
```
public final PsdOptions getPsdOptions()
```


Opzioni di conversione specifiche per Psd.


**Returns:**
[PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions)
### setPsdOptions(PsdOptions value) {#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-}
```
public final void setPsdOptions(PsdOptions value)
```


Opzioni di conversione specifiche per Psd.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions) |  |

### getWebpOptions() {#getWebpOptions--}
```
public final WebpOptions getWebpOptions()
```


Opzioni di conversione specifiche per Webp.


**Returns:**
[WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions)
### setWebpOptions(WebpOptions value) {#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-}
```
public final void setWebpOptions(WebpOptions value)
```


Opzioni di conversione specifiche per Webp.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Indica se convertire in un'immagine in scala di grigi.


**Returns:**
booleano
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Indica se convertire in un'immagine in scala di grigi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getRotateAngle() {#getRotateAngle--}
```
public final int getRotateAngle()
```


Angolo di rotazione dell'immagine.


**Returns:**
int
### setRotateAngle(int value) {#setRotateAngle-int-}
```
public final void setRotateAngle(int value)
```


Angolo di rotazione dell'immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Opzioni di conversione specifiche per Jpeg.


**Returns:**
[JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions)
### setJpegOptions(JpegOptions value) {#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Opzioni di conversione specifiche per Jpeg.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) |  |

### getFlipMode() {#getFlipMode--}
```
public final ImageFlipModes getFlipMode()
```


Modalità di ribaltamento dell'immagine.


**Returns:**
[ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes)
### setFlipMode(ImageFlipModes value) {#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-}
```
public final void setFlipMode(ImageFlipModes value)
```


Modalità di ribaltamento dell'immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes) |  |

### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Regola la luminosità dell'immagine.


**Returns:**
int
### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Regola la luminosità dell'immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getContrast() {#getContrast--}
```
public final int getContrast()
```


Regola il contrasto dell'immagine.


**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Regola il contrasto dell'immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getGamma() {#getGamma--}
```
public final float getGamma()
```


Regola la gamma dell'immagine.


**Returns:**
float
### setGamma(float value) {#setGamma-float-}
```
public final void setGamma(float value)
```


Regola la gamma dell'immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Ottiene il colore di sfondo


**Returns:**
com.aspose.ms.System.Drawing.Color - colore di sfondo

### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Imposta il colore di sfondo dove supportato dal formato di origine


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | backgroundColor | com.aspose.ms.System.Drawing.Color | colore di sfondo |
|

