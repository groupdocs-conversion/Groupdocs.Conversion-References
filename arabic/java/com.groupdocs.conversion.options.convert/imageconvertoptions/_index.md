---
title: "ImageConvertOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات التحويل إلى نوع ملف Image."
type: docs
weight: 18
url: /ar/java/com.groupdocs.conversion.options.convert/imageconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageConvertOptions extends CommonConvertOptions<ImageFileType> implements Serializable
```

خيارات التحويل إلى نوع ملف Image.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [ImageConvertOptions()](#ImageConvertOptions--) | يُنشئ مثيلًا جديدًا من الفئة [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions). |
|
## الحقول

| حقل | الوصف |
| --- | --- |
| [DEFAULT_DPI](#DEFAULT-DPI) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWidth()](#getWidth--) | العرض المطلوب للصورة بعد التحويل. |
|
|  | [setWidth(int value)](#setWidth-int-) | العرض المطلوب للصورة بعد التحويل. |
|
|  | [getHeight()](#getHeight--) | الارتفاع المطلوب للصورة بعد التحويل. |
|
|  | [setHeight(int value)](#setHeight-int-) | الارتفاع المطلوب للصورة بعد التحويل. |
|
|  | [getUsePdf()](#getUsePdf--) | إذا |
true
, يتم أولاً تحويل الإدخال إلى PDF وبعد ذلك إلى التنسيق المطلوب.
|
|  | [setUsePdf(boolean value)](#setUsePdf-boolean-) | إذا |
true
, يتم أولاً تحويل الإدخال إلى PDF وبعد ذلك إلى التنسيق المطلوب.
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | الدقة الأفقية المطلوبة للصورة بعد التحويل. |
|
|  | [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | الدقة الأفقية المطلوبة للصورة بعد التحويل. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | الدقة العمودية المطلوبة للصورة بعد التحويل. |
|
|  | [setVerticalResolution(int value)](#setVerticalResolution-int-) | الدقة العمودية المطلوبة للصورة بعد التحويل. |
|
|  | [getTiffOptions()](#getTiffOptions--) | خيارات التحويل الخاصة بـ Tiff. |
|
|  | [setTiffOptions(TiffOptions value)](#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-) | خيارات التحويل الخاصة بـ Tiff. |
|
|  | [getPsdOptions()](#getPsdOptions--) | خيارات التحويل الخاصة بـ Psd. |
|
|  | [setPsdOptions(PsdOptions value)](#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-) | خيارات التحويل الخاصة بـ Psd. |
|
|  | [getWebpOptions()](#getWebpOptions--) | خيارات التحويل الخاصة بـ Webp. |
|
|  | [setWebpOptions(WebpOptions value)](#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-) | خيارات التحويل الخاصة بـ Webp. |
|
|  | [getGrayscale()](#getGrayscale--) | يحدد ما إذا كان سيتم التحويل إلى صورة بتدرج الرمادي. |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | يحدد ما إذا كان سيتم التحويل إلى صورة بتدرج الرمادي. |
|
|  | [getRotateAngle()](#getRotateAngle--) | زاوية دوران الصورة. |
|
|  | [setRotateAngle(int value)](#setRotateAngle-int-) | زاوية دوران الصورة. |
|
|  | [getJpegOptions()](#getJpegOptions--) | خيارات التحويل الخاصة بـ Jpeg. |
|
|  | [setJpegOptions(JpegOptions value)](#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-) | خيارات التحويل الخاصة بـ Jpeg. |
|
|  | [getFlipMode()](#getFlipMode--) | وضع انعكاس الصورة. |
|
|  | [setFlipMode(ImageFlipModes value)](#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-) | وضع انعكاس الصورة. |
|
|  | [getBrightness()](#getBrightness--) | يضبط سطوع الصورة. |
|
|  | [setBrightness(int value)](#setBrightness-int-) | يضبط سطوع الصورة. |
|
|  | [getContrast()](#getContrast--) | يضبط تباين الصورة. |
|
|  | [setContrast(int value)](#setContrast-int-) | يضبط تباين الصورة. |
|
|  | [getGamma()](#getGamma--) | يضبط جاما الصورة. |
|
|  | [setGamma(float value)](#setGamma-float-) | يضبط جاما الصورة. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون الخلفية |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | يضبط لون الخلفية حيث يدعم ذلك تنسيق المصدر |
|
### ImageConvertOptions() {#ImageConvertOptions--}
```
public ImageConvertOptions()
```


يُنشئ مثيلًا جديدًا من الفئة [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions).


### DEFAULT_DPI {#DEFAULT-DPI}
```
public static final int DEFAULT_DPI
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


العرض المطلوب للصورة بعد التحويل.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


العرض المطلوب للصورة بعد التحويل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


الارتفاع المطلوب للصورة بعد التحويل.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


الارتفاع المطلوب للصورة بعد التحويل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


إذا
true
, يتم أولاً تحويل الإدخال إلى PDF وبعد ذلك إلى التنسيق المطلوب.


**Returns:**
منطقي
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


إذا
true
, يتم أولاً تحويل الإدخال إلى PDF وبعد ذلك إلى التنسيق المطلوب.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final int getHorizontalResolution()
```


الدقة الأفقية المطلوبة للصورة بعد التحويل. الدقة الافتراضية هي دقة ملف الإدخال أو 96 نقطة في البوصة.


**Returns:**
int
### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public final void setHorizontalResolution(int value)
```


الدقة الأفقية المطلوبة للصورة بعد التحويل. الدقة الافتراضية هي دقة ملف الإدخال أو 96 نقطة في البوصة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final int getVerticalResolution()
```


الدقة العمودية المطلوبة للصورة بعد التحويل. الدقة الافتراضية هي دقة ملف الإدخال أو 96 نقطة في البوصة.


**Returns:**
int
### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public final void setVerticalResolution(int value)
```


الدقة العمودية المطلوبة للصورة بعد التحويل. الدقة الافتراضية هي دقة ملف الإدخال أو 96 نقطة في البوصة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getTiffOptions() {#getTiffOptions--}
```
public final TiffOptions getTiffOptions()
```


خيارات التحويل الخاصة بـ Tiff.


**Returns:**
[TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions)
### setTiffOptions(TiffOptions value) {#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-}
```
public final void setTiffOptions(TiffOptions value)
```


خيارات التحويل الخاصة بـ Tiff.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions) |  |

### getPsdOptions() {#getPsdOptions--}
```
public final PsdOptions getPsdOptions()
```


خيارات التحويل الخاصة بـ Psd.


**Returns:**
[PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions)
### setPsdOptions(PsdOptions value) {#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-}
```
public final void setPsdOptions(PsdOptions value)
```


خيارات التحويل الخاصة بـ Psd.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions) |  |

### getWebpOptions() {#getWebpOptions--}
```
public final WebpOptions getWebpOptions()
```


خيارات التحويل الخاصة بـ Webp.


**Returns:**
[WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions)
### setWebpOptions(WebpOptions value) {#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-}
```
public final void setWebpOptions(WebpOptions value)
```


خيارات التحويل الخاصة بـ Webp.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


يحدد ما إذا كان سيتم التحويل إلى صورة بتدرج الرمادي.


**Returns:**
منطقي
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


يحدد ما إذا كان سيتم التحويل إلى صورة بتدرج الرمادي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getRotateAngle() {#getRotateAngle--}
```
public final int getRotateAngle()
```


زاوية دوران الصورة.


**Returns:**
int
### setRotateAngle(int value) {#setRotateAngle-int-}
```
public final void setRotateAngle(int value)
```


زاوية دوران الصورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


خيارات التحويل الخاصة بـ Jpeg.


**Returns:**
[JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions)
### setJpegOptions(JpegOptions value) {#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


خيارات التحويل الخاصة بـ Jpeg.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) |  |

### getFlipMode() {#getFlipMode--}
```
public final ImageFlipModes getFlipMode()
```


وضع انعكاس الصورة.


**Returns:**
[ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes)
### setFlipMode(ImageFlipModes value) {#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-}
```
public final void setFlipMode(ImageFlipModes value)
```


وضع انعكاس الصورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes) |  |

### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


يضبط سطوع الصورة.


**Returns:**
int
### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


يضبط سطوع الصورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getContrast() {#getContrast--}
```
public final int getContrast()
```


يضبط تباين الصورة.


**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


يضبط تباين الصورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getGamma() {#getGamma--}
```
public final float getGamma()
```


يضبط جاما الصورة.


**Returns:**
float
### setGamma(float value) {#setGamma-float-}
```
public final void setGamma(float value)
```


يضبط جاما الصورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


يحصل على لون الخلفية


**Returns:**
com.aspose.ms.System.Drawing.Color - لون الخلفية

### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


يضبط لون الخلفية حيث يدعم ذلك تنسيق المصدر


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | backgroundColor | com.aspose.ms.System.Drawing.Color | لون الخلفية |
|

