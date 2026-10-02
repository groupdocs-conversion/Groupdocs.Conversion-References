---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "转换为 Image 文件类型的选项。"
type: docs
weight: 18
url: /zh/java/com.groupdocs.conversion.options.convert/imageconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageConvertOptions extends CommonConvertOptions<ImageFileType> implements Serializable
```

转换为 Image 文件类型的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [ImageConvertOptions()](#ImageConvertOptions--) | 初始化 [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions) 类的新实例。 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
| [DEFAULT_DPI](#DEFAULT-DPI) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 转换后期望的图像宽度。 |
|
|  | [setWidth(int value)](#setWidth-int-) | 转换后期望的图像宽度。 |
|
|  | [getHeight()](#getHeight--) | 转换后期望的图像高度。 |
|
|  | [setHeight(int value)](#setHeight-int-) | 转换后期望的图像高度。 |
|
|  | [getUsePdf()](#getUsePdf--) | 如果 |
true
，输入首先被转换为 PDF，然后再转换为所需格式。
|
|  | [setUsePdf(boolean value)](#setUsePdf-boolean-) | 如果 |
true
，输入首先被转换为 PDF，然后再转换为所需格式。
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | 转换后期望的图像水平分辨率。 |
|
|  | [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | 转换后期望的图像水平分辨率。 |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | 转换后期望的图像垂直分辨率。 |
|
|  | [setVerticalResolution(int value)](#setVerticalResolution-int-) | 转换后期望的图像垂直分辨率。 |
|
|  | [getTiffOptions()](#getTiffOptions--) | Tiff 特定转换选项。 |
|
|  | [setTiffOptions(TiffOptions value)](#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-) | Tiff 特定转换选项。 |
|
|  | [getPsdOptions()](#getPsdOptions--) | Psd 特定转换选项。 |
|
|  | [setPsdOptions(PsdOptions value)](#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-) | Psd 特定转换选项。 |
|
|  | [getWebpOptions()](#getWebpOptions--) | Webp 特定转换选项。 |
|
|  | [setWebpOptions(WebpOptions value)](#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-) | Webp 特定转换选项。 |
|
|  | [getGrayscale()](#getGrayscale--) | 指示是否将图像转换为灰度图像。 |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | 指示是否将图像转换为灰度图像。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 图像旋转角度。 |
|
|  | [setRotateAngle(int value)](#setRotateAngle-int-) | 图像旋转角度。 |
|
|  | [getJpegOptions()](#getJpegOptions--) | Jpeg 特定转换选项。 |
|
|  | [setJpegOptions(JpegOptions value)](#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-) | Jpeg 特定转换选项。 |
|
|  | [getFlipMode()](#getFlipMode--) | 图像翻转模式。 |
|
|  | [setFlipMode(ImageFlipModes value)](#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-) | 图像翻转模式。 |
|
|  | [getBrightness()](#getBrightness--) | 调整图像亮度。 |
|
|  | [setBrightness(int value)](#setBrightness-int-) | 调整图像亮度。 |
|
|  | [getContrast()](#getContrast--) | 调整图像对比度。 |
|
|  | [setContrast(int value)](#setContrast-int-) | 调整图像对比度。 |
|
|  | [getGamma()](#getGamma--) | 调整图像伽马。 |
|
|  | [setGamma(float value)](#setGamma-float-) | 调整图像伽马。 |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | 获取背景颜色 |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | 在源格式支持的情况下设置背景颜色 |
|
### ImageConvertOptions() {#ImageConvertOptions--}
```
public ImageConvertOptions()
```


初始化 [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions) 类的新实例。


### DEFAULT_DPI {#DEFAULT-DPI}
```
public static final int DEFAULT_DPI
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


转换后期望的图像宽度。


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


转换后期望的图像宽度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


转换后期望的图像高度。


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


转换后期望的图像高度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


如果
true
，输入首先被转换为 PDF，然后再转换为所需格式。


**Returns:**
布尔
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


如果
true
，输入首先被转换为 PDF，然后再转换为所需格式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final int getHorizontalResolution()
```


转换后期望的图像水平分辨率。默认分辨率为输入文件的分辨率或 96 dpi。


**Returns:**
int
### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public final void setHorizontalResolution(int value)
```


转换后期望的图像水平分辨率。默认分辨率为输入文件的分辨率或 96 dpi。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final int getVerticalResolution()
```


转换后期望的图像垂直分辨率。默认分辨率为输入文件的分辨率或 96 dpi。


**Returns:**
int
### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public final void setVerticalResolution(int value)
```


转换后期望的图像垂直分辨率。默认分辨率为输入文件的分辨率或 96 dpi。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTiffOptions() {#getTiffOptions--}
```
public final TiffOptions getTiffOptions()
```


Tiff 特定转换选项。


**Returns:**
[TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions)
### setTiffOptions(TiffOptions value) {#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-}
```
public final void setTiffOptions(TiffOptions value)
```


Tiff 特定转换选项。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions) |  |

### getPsdOptions() {#getPsdOptions--}
```
public final PsdOptions getPsdOptions()
```


Psd 特定转换选项。


**Returns:**
[PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions)
### setPsdOptions(PsdOptions value) {#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-}
```
public final void setPsdOptions(PsdOptions value)
```


Psd 特定转换选项。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions) |  |

### getWebpOptions() {#getWebpOptions--}
```
public final WebpOptions getWebpOptions()
```


Webp 特定转换选项。


**Returns:**
[WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions)
### setWebpOptions(WebpOptions value) {#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-}
```
public final void setWebpOptions(WebpOptions value)
```


Webp 特定转换选项。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


指示是否将图像转换为灰度图像。


**Returns:**
布尔
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


指示是否将图像转换为灰度图像。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getRotateAngle() {#getRotateAngle--}
```
public final int getRotateAngle()
```


图像旋转角度。


**Returns:**
int
### setRotateAngle(int value) {#setRotateAngle-int-}
```
public final void setRotateAngle(int value)
```


图像旋转角度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Jpeg 特定转换选项。


**Returns:**
[JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions)
### setJpegOptions(JpegOptions value) {#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Jpeg 特定转换选项。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) |  |

### getFlipMode() {#getFlipMode--}
```
public final ImageFlipModes getFlipMode()
```


图像翻转模式。


**Returns:**
[ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes)
### setFlipMode(ImageFlipModes value) {#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-}
```
public final void setFlipMode(ImageFlipModes value)
```


图像翻转模式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes) |  |

### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


调整图像亮度。


**Returns:**
int
### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


调整图像亮度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getContrast() {#getContrast--}
```
public final int getContrast()
```


调整图像对比度。


**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


调整图像对比度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getGamma() {#getGamma--}
```
public final float getGamma()
```


调整图像伽马。


**Returns:**
float
### setGamma(float value) {#setGamma-float-}
```
public final void setGamma(float value)
```


调整图像伽马。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


获取背景颜色


**Returns:**
com.aspose.ms.System.Drawing.Color - 背景颜色

### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


在源格式支持的情况下设置背景颜色


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | backgroundColor | com.aspose.ms.System.Drawing.Color | 背景颜色 |
|

