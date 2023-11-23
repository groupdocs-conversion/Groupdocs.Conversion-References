---
title: ImageConvertOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for conversion to Image file type.
type: docs
weight: 18
url: /java/com.groupdocs.conversion.options.convert/imageconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageConvertOptions extends CommonConvertOptions<ImageFileType> implements Serializable
```

Options for conversion to Image file type.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageConvertOptions()](#ImageConvertOptions--) | Initializes new instance of [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions) class. |
## Fields

| Field | Description |
| --- | --- |
| [DEFAULT_DPI](#DEFAULT-DPI) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Desired image width after conversion. |
| [setWidth(int value)](#setWidth-int-) | Desired image width after conversion. |
| [getHeight()](#getHeight--) | Desired image height after conversion. |
| [setHeight(int value)](#setHeight-int-) | Desired image height after conversion. |
| [getUsePdf()](#getUsePdf--) | If  true , the input firstly is converted to PDF and after that to desired format. |
| [setUsePdf(boolean value)](#setUsePdf-boolean-) | If  true , the input firstly is converted to PDF and after that to desired format. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Desired image horizontal resolution after conversion. |
| [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Desired image horizontal resolution after conversion. |
| [getVerticalResolution()](#getVerticalResolution--) | Desired image vertical resolution after conversion. |
| [setVerticalResolution(int value)](#setVerticalResolution-int-) | Desired image vertical resolution after conversion. |
| [getTiffOptions()](#getTiffOptions--) | Tiff specific convert options. |
| [setTiffOptions(TiffOptions value)](#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-) | Tiff specific convert options. |
| [getPsdOptions()](#getPsdOptions--) | Psd specific convert options. |
| [setPsdOptions(PsdOptions value)](#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-) | Psd specific convert options. |
| [getWebpOptions()](#getWebpOptions--) | Webp specific convert options. |
| [setWebpOptions(WebpOptions value)](#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-) | Webp specific convert options. |
| [getGrayscale()](#getGrayscale--) | Indicates whether to convert into grayscale image. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Indicates whether to convert into grayscale image. |
| [getRotateAngle()](#getRotateAngle--) | Image rotation angle. |
| [setRotateAngle(int value)](#setRotateAngle-int-) | Image rotation angle. |
| [getJpegOptions()](#getJpegOptions--) | Jpeg specific convert options. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-) | Jpeg specific convert options. |
| [getFlipMode()](#getFlipMode--) | Image flip mode. |
| [setFlipMode(ImageFlipModes value)](#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-) | Image flip mode. |
| [getBrightness()](#getBrightness--) | Adjusts image brightness. |
| [setBrightness(int value)](#setBrightness-int-) | Adjusts image brightness. |
| [getContrast()](#getContrast--) | Adjusts image contrast. |
| [setContrast(int value)](#setContrast-int-) | Adjusts image contrast. |
| [getGamma()](#getGamma--) | Adjusts image gamma. |
| [setGamma(double value)](#setGamma-double-) | Adjusts image gamma. |
| [setGamma(float value)](#setGamma-float-) | Adjusts image gamma. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets background color |
| [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Sets background color where supported by the source format |
### ImageConvertOptions() {#ImageConvertOptions--}
```
public ImageConvertOptions()
```


Initializes new instance of [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions) class.

### DEFAULT_DPI {#DEFAULT-DPI}
```
public static final int DEFAULT_DPI
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Desired image width after conversion.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Desired image width after conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Desired image height after conversion.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Desired image height after conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


If  true , the input firstly is converted to PDF and after that to desired format.

**Returns:**
boolean
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


If  true , the input firstly is converted to PDF and after that to desired format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final int getHorizontalResolution()
```


Desired image horizontal resolution after conversion. The default resolution is the resolution of the input file or 96 dpi.

**Returns:**
int
### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public final void setHorizontalResolution(int value)
```


Desired image horizontal resolution after conversion. The default resolution is the resolution of the input file or 96 dpi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final int getVerticalResolution()
```


Desired image vertical resolution after conversion. The default resolution is the resolution of the input file or 96 dpi.

**Returns:**
int
### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public final void setVerticalResolution(int value)
```


Desired image vertical resolution after conversion. The default resolution is the resolution of the input file or 96 dpi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTiffOptions() {#getTiffOptions--}
```
public final TiffOptions getTiffOptions()
```


Tiff specific convert options.

**Returns:**
[TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions)
### setTiffOptions(TiffOptions value) {#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-}
```
public final void setTiffOptions(TiffOptions value)
```


Tiff specific convert options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions) |  |

### getPsdOptions() {#getPsdOptions--}
```
public final PsdOptions getPsdOptions()
```


Psd specific convert options.

**Returns:**
[PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions)
### setPsdOptions(PsdOptions value) {#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-}
```
public final void setPsdOptions(PsdOptions value)
```


Psd specific convert options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions) |  |

### getWebpOptions() {#getWebpOptions--}
```
public final WebpOptions getWebpOptions()
```


Webp specific convert options.

**Returns:**
[WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions)
### setWebpOptions(WebpOptions value) {#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-}
```
public final void setWebpOptions(WebpOptions value)
```


Webp specific convert options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Indicates whether to convert into grayscale image.

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Indicates whether to convert into grayscale image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRotateAngle() {#getRotateAngle--}
```
public final int getRotateAngle()
```


Image rotation angle.

**Returns:**
int
### setRotateAngle(int value) {#setRotateAngle-int-}
```
public final void setRotateAngle(int value)
```


Image rotation angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Jpeg specific convert options.

**Returns:**
[JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions)
### setJpegOptions(JpegOptions value) {#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Jpeg specific convert options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) |  |

### getFlipMode() {#getFlipMode--}
```
public final ImageFlipModes getFlipMode()
```


Image flip mode.

**Returns:**
[ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes)
### setFlipMode(ImageFlipModes value) {#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-}
```
public final void setFlipMode(ImageFlipModes value)
```


Image flip mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes) |  |

### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Adjusts image brightness.

**Returns:**
int
### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Adjusts image brightness.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getContrast() {#getContrast--}
```
public final int getContrast()
```


Adjusts image contrast.

**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Adjusts image contrast.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGamma() {#getGamma--}
```
public final double getGamma()
```


Adjusts image gamma.

**Returns:**
double
### setGamma(double value) {#setGamma-double-}
```
public final void setGamma(double value)
```


Adjusts image gamma.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setGamma(float value) {#setGamma-float-}
```
public final void setGamma(float value)
```


Adjusts image gamma.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Gets background color

**Returns:**
com.aspose.ms.System.Drawing.Color - background color
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Sets background color where supported by the source format

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color | background color |

