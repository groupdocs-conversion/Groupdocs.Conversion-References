---
title: "ImageConvertOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры конвертации в тип файла Image."
type: docs
weight: 18
url: /ru/nodejs-java/com.groupdocs.conversion.options.convert/imageconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageConvertOptions extends CommonConvertOptions<ImageFileType> implements Serializable
```

Параметры конвертации в тип файла Image.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageConvertOptions()](#ImageConvertOptions--) | Инициализирует новый экземпляр класса [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions). |
## Поля

| Поле | Описание |
| --- | --- |
| [DEFAULT_DPI](#DEFAULT-DPI) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getWidth()](#getWidth--) | Желаемая ширина изображения после конвертации. |
| [setWidth(int value)](#setWidth-int-) | Желаемая ширина изображения после конвертации. |
| [getHeight()](#getHeight--) | Желаемая высота изображения после конвертации. |
| [setHeight(int value)](#setHeight-int-) | Желаемая высота изображения после конвертации. |
| [getUsePdf()](#getUsePdf--) | Если true, входные данные сначала конвертируются в PDF, а затем в требуемый формат. |
| [setUsePdf(boolean value)](#setUsePdf-boolean-) | Если true, входные данные сначала конвертируются в PDF, а затем в требуемый формат. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Желаемое горизонтальное разрешение изображения после конвертации. |
| [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Желаемое горизонтальное разрешение изображения после конвертации. |
| [getVerticalResolution()](#getVerticalResolution--) | Желаемое вертикальное разрешение изображения после конвертации. |
| [setVerticalResolution(int value)](#setVerticalResolution-int-) | Желаемое вертикальное разрешение изображения после конвертации. |
| [getTiffOptions()](#getTiffOptions--) | Специфические параметры конвертации Tiff. |
| [setTiffOptions(TiffOptions value)](#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-) | Специфические параметры конвертации Tiff. |
| [getPsdOptions()](#getPsdOptions--) | Специфические параметры конвертации Psd. |
| [setPsdOptions(PsdOptions value)](#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-) | Специфические параметры конвертации Psd. |
| [getWebpOptions()](#getWebpOptions--) | Специфические параметры конвертации Webp. |
| [setWebpOptions(WebpOptions value)](#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-) | Специфические параметры конвертации Webp. |
| [getGrayscale()](#getGrayscale--) | Указывает, следует ли конвертировать в изображение в градациях серого. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Указывает, следует ли конвертировать в изображение в градациях серого. |
| [getRotateAngle()](#getRotateAngle--) | Угол вращения изображения. |
| [setRotateAngle(int value)](#setRotateAngle-int-) | Угол вращения изображения. |
| [getJpegOptions()](#getJpegOptions--) | Специфические параметры конвертации Jpeg. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-) | Специфические параметры конвертации Jpeg. |
| [getFlipMode()](#getFlipMode--) | Режим отражения изображения. |
| [setFlipMode(ImageFlipModes value)](#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-) | Режим отражения изображения. |
| [getBrightness()](#getBrightness--) | Регулирует яркость изображения. |
| [setBrightness(int value)](#setBrightness-int-) | Регулирует яркость изображения. |
| [getContrast()](#getContrast--) | Регулирует контраст изображения. |
| [setContrast(int value)](#setContrast-int-) | Регулирует контраст изображения. |
| [getGamma()](#getGamma--) | Регулирует гамму изображения. |
| [setGamma(double value)](#setGamma-double-) | Регулирует гамму изображения. |
| [setGamma(float value)](#setGamma-float-) | Регулирует гамму изображения. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает цвет фона |
| [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Устанавливает цвет фона, если он поддерживается исходным форматом |
### ImageConvertOptions() {#ImageConvertOptions--}
```
public ImageConvertOptions()
```


Инициализирует новый экземпляр класса [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions).

### DEFAULT_DPI {#DEFAULT-DPI}
```
public static final int DEFAULT_DPI
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Желаемая ширина изображения после конвертации.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Желаемая ширина изображения после конвертации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Желаемая высота изображения после конвертации.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Желаемая высота изображения после конвертации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


Если true, входные данные сначала конвертируются в PDF, а затем в требуемый формат.

**Returns:**
boolean
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


Если true, входные данные сначала конвертируются в PDF, а затем в требуемый формат.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final int getHorizontalResolution()
```


Желаемое горизонтальное разрешение изображения после конвертации. Разрешение по умолчанию — разрешение входного файла или 96 dpi.

**Returns:**
int
### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public final void setHorizontalResolution(int value)
```


Желаемое горизонтальное разрешение изображения после конвертации. Разрешение по умолчанию — разрешение входного файла или 96 dpi.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final int getVerticalResolution()
```


Желаемое вертикальное разрешение изображения после конвертации. Разрешение по умолчанию — разрешение входного файла или 96 dpi.

**Returns:**
int
### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public final void setVerticalResolution(int value)
```


Желаемое вертикальное разрешение изображения после конвертации. Разрешение по умолчанию — разрешение входного файла или 96 dpi.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getTiffOptions() {#getTiffOptions--}
```
public final TiffOptions getTiffOptions()
```


Специфические параметры конвертации Tiff.

**Returns:**
[TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions)
### setTiffOptions(TiffOptions value) {#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-}
```
public final void setTiffOptions(TiffOptions value)
```


Специфические параметры конвертации Tiff.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions) |  |

### getPsdOptions() {#getPsdOptions--}
```
public final PsdOptions getPsdOptions()
```


Специфические параметры конвертации Psd.

**Returns:**
[PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions)
### setPsdOptions(PsdOptions value) {#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-}
```
public final void setPsdOptions(PsdOptions value)
```


Специфические параметры конвертации Psd.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions) |  |

### getWebpOptions() {#getWebpOptions--}
```
public final WebpOptions getWebpOptions()
```


Специфические параметры конвертации Webp.

**Returns:**
[WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions)
### setWebpOptions(WebpOptions value) {#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-}
```
public final void setWebpOptions(WebpOptions value)
```


Специфические параметры конвертации Webp.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Указывает, следует ли конвертировать в изображение в градациях серого.

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Указывает, следует ли конвертировать в изображение в градациях серого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getRotateAngle() {#getRotateAngle--}
```
public final int getRotateAngle()
```


Угол вращения изображения.

**Returns:**
int
### setRotateAngle(int value) {#setRotateAngle-int-}
```
public final void setRotateAngle(int value)
```


Угол вращения изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Специфические параметры конвертации Jpeg.

**Returns:**
[JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions)
### setJpegOptions(JpegOptions value) {#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Специфические параметры конвертации Jpeg.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) |  |

### getFlipMode() {#getFlipMode--}
```
public final ImageFlipModes getFlipMode()
```


Режим отражения изображения.

**Returns:**
[ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes)
### setFlipMode(ImageFlipModes value) {#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-}
```
public final void setFlipMode(ImageFlipModes value)
```


Режим отражения изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes) |  |

### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Регулирует яркость изображения.

**Returns:**
int
### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Регулирует яркость изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getContrast() {#getContrast--}
```
public final int getContrast()
```


Регулирует контраст изображения.

**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Регулирует контраст изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getGamma() {#getGamma--}
```
public final double getGamma()
```


Регулирует гамму изображения.

**Returns:**
double
### setGamma(double value) {#setGamma-double-}
```
public final void setGamma(double value)
```


Регулирует гамму изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setGamma(float value) {#setGamma-float-}
```
public final void setGamma(float value)
```


Регулирует гамму изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Получает цвет фона

**Returns:**
com.aspose.ms.System.Drawing.Color - цвет фона
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Устанавливает цвет фона, если он поддерживается исходным форматом

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color | цвет фона |

