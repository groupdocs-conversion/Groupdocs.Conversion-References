---
title: "PdfConvertOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "Pdf फ़ाइल प्रकार में रूपांतरण के विकल्प।"
type: docs
weight: 25
url: /hi/java/com.groupdocs.conversion.options.convert/pdfconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class PdfConvertOptions extends CommonConvertOptions<PdfFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Pdf फ़ाइल प्रकार में रूपांतरण के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PdfConvertOptions()](#PdfConvertOptions--) | नया उदाहरण प्रारंभ करता है [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions) वर्ग का। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getDpi()](#getDpi--) | परिवर्तन के बाद वांछित पृष्ठ DPI। |
|
|  | [setDpi(int value)](#setDpi-int-) | परिवर्तन के बाद वांछित पृष्ठ DPI। |
|
|  | [getPassword()](#getPassword--) | यदि आप परिवर्तित दस्तावेज़ को पासवर्ड से सुरक्षित करना चाहते हैं तो इस प्रॉपर्टी को सेट करें। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | यदि आप परिवर्तित दस्तावेज़ को पासवर्ड से सुरक्षित करना चाहते हैं तो इस प्रॉपर्टी को सेट करें। |
|
|  | [getMarginTop()](#getMarginTop--) | परिवर्तन के बाद बिंदुओं में वांछित पृष्ठ शीर्ष मार्जिन। |
|
|  | [setMarginTop(float value)](#setMarginTop-float-) | परिवर्तन के बाद बिंदुओं में वांछित पृष्ठ शीर्ष मार्जिन। |
|
|  | [getMarginBottom()](#getMarginBottom--) | परिवर्तन के बाद बिंदुओं में वांछित पृष्ठ निचला मार्जिन। |
|
|  | [setMarginBottom(float value)](#setMarginBottom-float-) | परिवर्तन के बाद बिंदुओं में वांछित पृष्ठ निचला मार्जिन। |
|
|  | [getMarginLeft()](#getMarginLeft--) | परिवर्तन के बाद बिंदुओं में वांछित पृष्ठ बायाँ मार्जिन। |
|
|  | [setMarginLeft(float value)](#setMarginLeft-float-) | परिवर्तन के बाद बिंदुओं में वांछित पृष्ठ बायाँ मार्जिन। |
|
|  | [getMarginRight()](#getMarginRight--) | रूपांतरण के बाद बिंदुओं में वांछित पृष्ठ का दायाँ मार्जिन। |
|
|  | [setMarginRight(float value)](#setMarginRight-float-) | रूपांतरण के बाद बिंदुओं में वांछित पृष्ठ का दायाँ मार्जिन। |
|
|  | [getPdfOptions()](#getPdfOptions--) | Pdf विशिष्ट परिवर्तन विकल्प |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-) | Pdf विशिष्ट परिवर्तन विकल्प |
|
|  | [getRotate()](#getRotate--) | पृष्ठ घूर्णन |
|
|  | [setRotate(Rotation value)](#setRotate-com.groupdocs.conversion.options.convert.Rotation-) | पृष्ठ घूर्णन |
|
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
### PdfConvertOptions() {#PdfConvertOptions--}
```
public PdfConvertOptions()
```


नया उदाहरण प्रारंभ करता है [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions) वर्ग का।


### getDpi() {#getDpi--}
```
public final int getDpi()
```


रूपांतरण के बाद वांछित पृष्ठ DPI। डिफ़ॉल्ट रिज़ॉल्यूशन है: 96 dpi।


**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


रूपांतरण के बाद वांछित पृष्ठ DPI। डिफ़ॉल्ट रिज़ॉल्यूशन है: 96 dpi।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


यदि आप परिवर्तित दस्तावेज़ को पासवर्ड से सुरक्षित करना चाहते हैं तो इस प्रॉपर्टी को सेट करें।


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


यदि आप परिवर्तित दस्तावेज़ को पासवर्ड से सुरक्षित करना चाहते हैं तो इस प्रॉपर्टी को सेट करें।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getMarginTop() {#getMarginTop--}
```
public final float getMarginTop()
```


परिवर्तन के बाद बिंदुओं में वांछित पृष्ठ शीर्ष मार्जिन।


**Returns:**
float
### setMarginTop(float value) {#setMarginTop-float-}
```
public final void setMarginTop(float value)
```


परिवर्तन के बाद बिंदुओं में वांछित पृष्ठ शीर्ष मार्जिन।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### getMarginBottom() {#getMarginBottom--}
```
public final float getMarginBottom()
```


परिवर्तन के बाद बिंदुओं में वांछित पृष्ठ निचला मार्जिन।


**Returns:**
float
### setMarginBottom(float value) {#setMarginBottom-float-}
```
public final void setMarginBottom(float value)
```


परिवर्तन के बाद बिंदुओं में वांछित पृष्ठ निचला मार्जिन।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


परिवर्तन के बाद बिंदुओं में वांछित पृष्ठ बायाँ मार्जिन।


**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


परिवर्तन के बाद बिंदुओं में वांछित पृष्ठ बायाँ मार्जिन।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


रूपांतरण के बाद बिंदुओं में वांछित पृष्ठ का दायाँ मार्जिन।


**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


रूपांतरण के बाद बिंदुओं में वांछित पृष्ठ का दायाँ मार्जिन।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Pdf विशिष्ट परिवर्तन विकल्प


**Returns:**
[PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Pdf विशिष्ट परिवर्तन विकल्प


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions) |  |

### getRotate() {#getRotate--}
```
public final Rotation getRotate()
```


पृष्ठ घूर्णन


**Returns:**
[Rotation](../../com.groupdocs.conversion.options.convert/rotation)
### setRotate(Rotation value) {#setRotate-com.groupdocs.conversion.options.convert.Rotation-}
```
public final void setRotate(Rotation value)
```


पृष्ठ घूर्णन


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Rotation](../../com.groupdocs.conversion.options.convert/rotation) |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


रूपांतरण के बाद पृष्ठ अभिविन्यास प्राप्त करता है


**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


रूपांतरण के बाद वांछित पृष्ठ अभिविन्यास सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


रूपांतरण के बाद वांछित पृष्ठ आकार प्राप्त करता है


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


रूपांतरण के बाद वांछित पृष्ठ आकार सेट करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


यदि PageSize.Custom पर सेट है तो बिंदुओं में निर्दिष्ट पृष्ठ चौड़ाई


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


वांछित पृष्ठ चौड़ाई सेट करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


यदि PageSize.Custom पर सेट है तो बिंदुओं में निर्दिष्ट पृष्ठ ऊँचाई


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


वांछित पृष्ठ ऊँचाई सेट करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageHeight | float |  |

