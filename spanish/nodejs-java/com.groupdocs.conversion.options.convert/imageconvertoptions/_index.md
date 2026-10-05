---
title: "ImageConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para la conversión al tipo de archivo Imagen."
type: docs
weight: 18
url: /es/nodejs-java/com.groupdocs.conversion.options.convert/imageconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageConvertOptions extends CommonConvertOptions<ImageFileType> implements Serializable
```

Opciones para la conversión al tipo de archivo Imagen.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageConvertOptions()](#ImageConvertOptions--) | Inicializa una nueva instancia de la clase [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions). |
## Campos

| Campo | Descripción |
| --- | --- |
| [DEFAULT_DPI](#DEFAULT-DPI) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getWidth()](#getWidth--) | Ancho deseado de la imagen después de la conversión. |
| [setWidth(int value)](#setWidth-int-) | Ancho deseado de la imagen después de la conversión. |
| [getHeight()](#getHeight--) | Altura deseada de la imagen después de la conversión. |
| [setHeight(int value)](#setHeight-int-) | Altura deseada de la imagen después de la conversión. |
| [getUsePdf()](#getUsePdf--) | Si  true , la entrada se convierte primero a PDF y después al formato deseado. |
| [setUsePdf(boolean value)](#setUsePdf-boolean-) | Si  true , la entrada se convierte primero a PDF y después al formato deseado. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Resolución horizontal deseada de la imagen después de la conversión. |
| [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Resolución horizontal deseada de la imagen después de la conversión. |
| [getVerticalResolution()](#getVerticalResolution--) | Resolución vertical deseada de la imagen después de la conversión. |
| [setVerticalResolution(int value)](#setVerticalResolution-int-) | Resolución vertical deseada de la imagen después de la conversión. |
| [getTiffOptions()](#getTiffOptions--) | Opciones de conversión específicas de Tiff. |
| [setTiffOptions(TiffOptions value)](#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-) | Opciones de conversión específicas de Tiff. |
| [getPsdOptions()](#getPsdOptions--) | Opciones de conversión específicas de Psd. |
| [setPsdOptions(PsdOptions value)](#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-) | Opciones de conversión específicas de Psd. |
| [getWebpOptions()](#getWebpOptions--) | Opciones de conversión específicas de Webp. |
| [setWebpOptions(WebpOptions value)](#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-) | Opciones de conversión específicas de Webp. |
| [getGrayscale()](#getGrayscale--) | Indica si se debe convertir a una imagen en escala de grises. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Indica si se debe convertir a una imagen en escala de grises. |
| [getRotateAngle()](#getRotateAngle--) | Ángulo de rotación de la imagen. |
| [setRotateAngle(int value)](#setRotateAngle-int-) | Ángulo de rotación de la imagen. |
| [getJpegOptions()](#getJpegOptions--) | Opciones de conversión específicas de Jpeg. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-) | Opciones de conversión específicas de Jpeg. |
| [getFlipMode()](#getFlipMode--) | Modo de volteo de la imagen. |
| [setFlipMode(ImageFlipModes value)](#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-) | Modo de volteo de la imagen. |
| [getBrightness()](#getBrightness--) | Ajusta el brillo de la imagen. |
| [setBrightness(int value)](#setBrightness-int-) | Ajusta el brillo de la imagen. |
| [getContrast()](#getContrast--) | Ajusta el contraste de la imagen. |
| [setContrast(int value)](#setContrast-int-) | Ajusta el contraste de la imagen. |
| [getGamma()](#getGamma--) | Ajusta la gamma de la imagen. |
| [setGamma(double value)](#setGamma-double-) | Ajusta la gamma de la imagen. |
| [setGamma(float value)](#setGamma-float-) | Ajusta la gamma de la imagen. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene el color de fondo |
| [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Establece el color de fondo donde el formato de origen lo permite |
### ImageConvertOptions() {#ImageConvertOptions--}
```
public ImageConvertOptions()
```


Inicializa una nueva instancia de la clase [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions).

### DEFAULT_DPI {#DEFAULT-DPI}
```
public static final int DEFAULT_DPI
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ancho deseado de la imagen después de la conversión.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ancho deseado de la imagen después de la conversión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Altura deseada de la imagen después de la conversión.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Altura deseada de la imagen después de la conversión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


Si  true , la entrada se convierte primero a PDF y después al formato deseado.

**Returns:**
boolean
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


Si  true , la entrada se convierte primero a PDF y después al formato deseado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final int getHorizontalResolution()
```


Resolución horizontal deseada de la imagen después de la conversión. La resolución predeterminada es la del archivo de entrada o 96 dpi.

**Returns:**
int
### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public final void setHorizontalResolution(int value)
```


Resolución horizontal deseada de la imagen después de la conversión. La resolución predeterminada es la del archivo de entrada o 96 dpi.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final int getVerticalResolution()
```


Resolución vertical deseada de la imagen después de la conversión. La resolución predeterminada es la del archivo de entrada o 96 dpi.

**Returns:**
int
### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public final void setVerticalResolution(int value)
```


Resolución vertical deseada de la imagen después de la conversión. La resolución predeterminada es la del archivo de entrada o 96 dpi.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTiffOptions() {#getTiffOptions--}
```
public final TiffOptions getTiffOptions()
```


Opciones de conversión específicas de Tiff.

**Returns:**
[TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions)
### setTiffOptions(TiffOptions value) {#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-}
```
public final void setTiffOptions(TiffOptions value)
```


Opciones de conversión específicas de Tiff.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions) |  |

### getPsdOptions() {#getPsdOptions--}
```
public final PsdOptions getPsdOptions()
```


Opciones de conversión específicas de Psd.

**Returns:**
[PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions)
### setPsdOptions(PsdOptions value) {#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-}
```
public final void setPsdOptions(PsdOptions value)
```


Opciones de conversión específicas de Psd.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions) |  |

### getWebpOptions() {#getWebpOptions--}
```
public final WebpOptions getWebpOptions()
```


Opciones de conversión específicas de Webp.

**Returns:**
[WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions)
### setWebpOptions(WebpOptions value) {#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-}
```
public final void setWebpOptions(WebpOptions value)
```


Opciones de conversión específicas de Webp.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Indica si se debe convertir a una imagen en escala de grises.

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Indica si se debe convertir a una imagen en escala de grises.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getRotateAngle() {#getRotateAngle--}
```
public final int getRotateAngle()
```


Ángulo de rotación de la imagen.

**Returns:**
int
### setRotateAngle(int value) {#setRotateAngle-int-}
```
public final void setRotateAngle(int value)
```


Ángulo de rotación de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Opciones de conversión específicas de Jpeg.

**Returns:**
[JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions)
### setJpegOptions(JpegOptions value) {#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Opciones de conversión específicas de Jpeg.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) |  |

### getFlipMode() {#getFlipMode--}
```
public final ImageFlipModes getFlipMode()
```


Modo de volteo de la imagen.

**Returns:**
[ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes)
### setFlipMode(ImageFlipModes value) {#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-}
```
public final void setFlipMode(ImageFlipModes value)
```


Modo de volteo de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes) |  |

### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Ajusta el brillo de la imagen.

**Returns:**
int
### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Ajusta el brillo de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getContrast() {#getContrast--}
```
public final int getContrast()
```


Ajusta el contraste de la imagen.

**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Ajusta el contraste de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getGamma() {#getGamma--}
```
public final double getGamma()
```


Ajusta la gamma de la imagen.

**Returns:**
double
### setGamma(double value) {#setGamma-double-}
```
public final void setGamma(double value)
```


Ajusta la gamma de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setGamma(float value) {#setGamma-float-}
```
public final void setGamma(float value)
```


Ajusta la gamma de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Obtiene el color de fondo

**Returns:**
com.aspose.ms.System.Drawing.Color - color de fondo
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Establece el color de fondo donde el formato de origen lo permite

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color | color de fondo |

