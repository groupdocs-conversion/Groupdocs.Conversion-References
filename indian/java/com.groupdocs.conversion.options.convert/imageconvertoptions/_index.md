---
title: "ImageConvertOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "Image फ़ाइल प्रकार में रूपांतरण के विकल्प।"
type: docs
weight: 18
url: /hi/java/com.groupdocs.conversion.options.convert/imageconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageConvertOptions extends CommonConvertOptions<ImageFileType> implements Serializable
```

Image फ़ाइल प्रकार में रूपांतरण के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [ImageConvertOptions()](#ImageConvertOptions--) | नए उदाहरण को प्रारंभ करता है [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions) वर्ग का। |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [DEFAULT_DPI](#DEFAULT-DPI) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getWidth()](#getWidth--) | परिवर्तन के बाद वांछित छवि की चौड़ाई। |
|
|  | [setWidth(int value)](#setWidth-int-) | परिवर्तन के बाद वांछित छवि की चौड़ाई। |
|
|  | [getHeight()](#getHeight--) | परिवर्तन के बाद वांछित छवि की ऊँचाई। |
|
|  | [setHeight(int value)](#setHeight-int-) | परिवर्तन के बाद वांछित छवि की ऊँचाई। |
|
|  | [getUsePdf()](#getUsePdf--) | यदि |
true
, इनपुट पहले PDF में परिवर्तित होता है और उसके बाद वांछित प्रारूप में।
|
|  | [setUsePdf(boolean value)](#setUsePdf-boolean-) | यदि |
true
, इनपुट पहले PDF में परिवर्तित होता है और उसके बाद वांछित प्रारूप में।
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | परिवर्तन के बाद वांछित छवि की क्षैतिज रिज़ॉल्यूशन। |
|
|  | [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | परिवर्तन के बाद वांछित छवि की क्षैतिज रिज़ॉल्यूशन। |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | परिवर्तन के बाद वांछित छवि की लंबवत रिज़ॉल्यूशन। |
|
|  | [setVerticalResolution(int value)](#setVerticalResolution-int-) | परिवर्तन के बाद वांछित छवि की लंबवत रिज़ॉल्यूशन। |
|
|  | [getTiffOptions()](#getTiffOptions--) | Tiff विशेष रूपांतरण विकल्प। |
|
|  | [setTiffOptions(TiffOptions value)](#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-) | Tiff विशेष रूपांतरण विकल्प। |
|
|  | [getPsdOptions()](#getPsdOptions--) | Psd विशेष रूपांतरण विकल्प। |
|
|  | [setPsdOptions(PsdOptions value)](#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-) | Psd विशेष रूपांतरण विकल्प। |
|
|  | [getWebpOptions()](#getWebpOptions--) | Webp विशेष रूपांतरण विकल्प। |
|
|  | [setWebpOptions(WebpOptions value)](#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-) | Webp विशेष रूपांतरण विकल्प। |
|
|  | [getGrayscale()](#getGrayscale--) | निर्देशित करता है कि क्या ग्रेस्केल छवि में रूपांतरित करना है। |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | निर्देशित करता है कि क्या ग्रेस्केल छवि में रूपांतरित करना है। |
|
|  | [getRotateAngle()](#getRotateAngle--) | छवि घुमाव कोण। |
|
|  | [setRotateAngle(int value)](#setRotateAngle-int-) | छवि घुमाव कोण। |
|
|  | [getJpegOptions()](#getJpegOptions--) | Jpeg विशेष रूपांतरण विकल्प। |
|
|  | [setJpegOptions(JpegOptions value)](#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-) | Jpeg विशेष रूपांतरण विकल्प। |
|
|  | [getFlipMode()](#getFlipMode--) | छवि फ़्लिप मोड। |
|
|  | [setFlipMode(ImageFlipModes value)](#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-) | छवि फ़्लिप मोड। |
|
|  | [getBrightness()](#getBrightness--) | छवि की चमक को समायोजित करता है। |
|
|  | [setBrightness(int value)](#setBrightness-int-) | छवि की चमक को समायोजित करता है। |
|
|  | [getContrast()](#getContrast--) | छवि के कंट्रास्ट को समायोजित करता है। |
|
|  | [setContrast(int value)](#setContrast-int-) | छवि के कंट्रास्ट को समायोजित करता है। |
|
|  | [getGamma()](#getGamma--) | छवि के गामा को समायोजित करता है। |
|
|  | [setGamma(float value)](#setGamma-float-) | छवि के गामा को समायोजित करता है। |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | पृष्ठभूमि रंग प्राप्त करता है |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | स्रोत प्रारूप द्वारा समर्थित होने पर पृष्ठभूमि रंग सेट करता है |
|
### ImageConvertOptions() {#ImageConvertOptions--}
```
public ImageConvertOptions()
```


नए उदाहरण को प्रारंभ करता है [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions) वर्ग का।


### DEFAULT_DPI {#DEFAULT-DPI}
```
public static final int DEFAULT_DPI
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


परिवर्तन के बाद वांछित छवि की चौड़ाई।


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


परिवर्तन के बाद वांछित छवि की चौड़ाई।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


परिवर्तन के बाद वांछित छवि की ऊँचाई।


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


परिवर्तन के बाद वांछित छवि की ऊँचाई।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


यदि
true
, इनपुट पहले PDF में परिवर्तित होता है और उसके बाद वांछित प्रारूप में।


**Returns:**
बूलियन
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


यदि
true
, इनपुट पहले PDF में परिवर्तित होता है और उसके बाद वांछित प्रारूप में।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final int getHorizontalResolution()
```


परिवर्तन के बाद वांछित छवि की क्षैतिज रिज़ॉल्यूशन। डिफ़ॉल्ट रिज़ॉल्यूशन इनपुट फ़ाइल की रिज़ॉल्यूशन या 96 dpi है।


**Returns:**
int
### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public final void setHorizontalResolution(int value)
```


परिवर्तन के बाद वांछित छवि की क्षैतिज रिज़ॉल्यूशन। डिफ़ॉल्ट रिज़ॉल्यूशन इनपुट फ़ाइल की रिज़ॉल्यूशन या 96 dpi है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final int getVerticalResolution()
```


परिवर्तन के बाद वांछित छवि की लंबवत रिज़ॉल्यूशन। डिफ़ॉल्ट रिज़ॉल्यूशन इनपुट फ़ाइल की रिज़ॉल्यूशन या 96 dpi है।


**Returns:**
int
### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public final void setVerticalResolution(int value)
```


परिवर्तन के बाद वांछित छवि की लंबवत रिज़ॉल्यूशन। डिफ़ॉल्ट रिज़ॉल्यूशन इनपुट फ़ाइल की रिज़ॉल्यूशन या 96 dpi है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getTiffOptions() {#getTiffOptions--}
```
public final TiffOptions getTiffOptions()
```


Tiff विशेष रूपांतरण विकल्प।


**Returns:**
[TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions)
### setTiffOptions(TiffOptions value) {#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-}
```
public final void setTiffOptions(TiffOptions value)
```


Tiff विशेष रूपांतरण विकल्प।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions) |  |

### getPsdOptions() {#getPsdOptions--}
```
public final PsdOptions getPsdOptions()
```


Psd विशेष रूपांतरण विकल्प।


**Returns:**
[PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions)
### setPsdOptions(PsdOptions value) {#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-}
```
public final void setPsdOptions(PsdOptions value)
```


Psd विशेष रूपांतरण विकल्प।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions) |  |

### getWebpOptions() {#getWebpOptions--}
```
public final WebpOptions getWebpOptions()
```


Webp विशेष रूपांतरण विकल्प।


**Returns:**
[WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions)
### setWebpOptions(WebpOptions value) {#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-}
```
public final void setWebpOptions(WebpOptions value)
```


Webp विशेष रूपांतरण विकल्प।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


निर्देशित करता है कि क्या ग्रेस्केल छवि में रूपांतरित करना है।


**Returns:**
बूलियन
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


निर्देशित करता है कि क्या ग्रेस्केल छवि में रूपांतरित करना है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getRotateAngle() {#getRotateAngle--}
```
public final int getRotateAngle()
```


छवि घुमाव कोण।


**Returns:**
int
### setRotateAngle(int value) {#setRotateAngle-int-}
```
public final void setRotateAngle(int value)
```


छवि घुमाव कोण।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Jpeg विशेष रूपांतरण विकल्प।


**Returns:**
[JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions)
### setJpegOptions(JpegOptions value) {#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Jpeg विशेष रूपांतरण विकल्प।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) |  |

### getFlipMode() {#getFlipMode--}
```
public final ImageFlipModes getFlipMode()
```


छवि फ़्लिप मोड।


**Returns:**
[ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes)
### setFlipMode(ImageFlipModes value) {#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-}
```
public final void setFlipMode(ImageFlipModes value)
```


छवि फ़्लिप मोड।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes) |  |

### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


छवि की चमक को समायोजित करता है।


**Returns:**
int
### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


छवि की चमक को समायोजित करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getContrast() {#getContrast--}
```
public final int getContrast()
```


छवि के कंट्रास्ट को समायोजित करता है।


**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


छवि के कंट्रास्ट को समायोजित करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getGamma() {#getGamma--}
```
public final float getGamma()
```


छवि के गामा को समायोजित करता है।


**Returns:**
float
### setGamma(float value) {#setGamma-float-}
```
public final void setGamma(float value)
```


छवि के गामा को समायोजित करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


पृष्ठभूमि रंग प्राप्त करता है


**Returns:**
com.aspose.ms.System.Drawing.Color - पृष्ठभूमि रंग

### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


स्रोत प्रारूप द्वारा समर्थित होने पर पृष्ठभूमि रंग सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | backgroundColor | com.aspose.ms.System.Drawing.Color | पृष्ठभूमि रंग |
|

