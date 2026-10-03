---
title: "WordProcessingConvertOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "WordProcessing फ़ाइल प्रकार में रूपांतरण के विकल्प।"
type: docs
weight: 48
url: /hi/java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions), [com.groupdocs.conversion.options.convert.IPdfRecognitionModeOptions](../../com.groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions)
```
public class WordProcessingConvertOptions extends CommonConvertOptions<WordProcessingFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions, IPdfRecognitionModeOptions
```

WordProcessing फ़ाइल प्रकार में रूपांतरण के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | नया उदाहरण प्रारंभ करता है [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions) क्लास का। |
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
|  | [getRtfOptions()](#getRtfOptions--) | RTF विशिष्ट परिवर्तन विकल्प |
|
|  | [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | RTF विशिष्ट परिवर्तन विकल्प |
|
|  | [getZoom()](#getZoom--) | ज़ूम स्तर को प्रतिशत में निर्दिष्ट करता है। |
|
|  | [setZoom(int value)](#setZoom-int-) | ज़ूम स्तर को प्रतिशत में निर्दिष्ट करता है। |
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
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
| [getPdfRecognitionMode()](#getPdfRecognitionMode--) |  |
| [setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)](#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-) |  |
|  | [getMarkdownOptions()](#getMarkdownOptions--) | प्राप्त करता है |
|
|  | [setMarkdownOptions(MarkdownOptions markdownOptions)](#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-) | सेट करता है |
|
### WordProcessingConvertOptions() {#WordProcessingConvertOptions--}
```
public WordProcessingConvertOptions()
```


नया उदाहरण प्रारंभ करता है [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions) क्लास का।


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

### getRtfOptions() {#getRtfOptions--}
```
public final RtfOptions getRtfOptions()
```


RTF विशिष्ट परिवर्तन विकल्प


**Returns:**
[RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions)
### setRtfOptions(RtfOptions value) {#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-}
```
public final void setRtfOptions(RtfOptions value)
```


RTF विशिष्ट परिवर्तन विकल्प


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions) |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


ज़ूम स्तर को प्रतिशत में निर्दिष्ट करता है। डिफ़ॉल्ट 100 है।
डिफ़ॉल्ट ज़ूम Microsoft Word 2010 तक समर्थित है। Microsoft Word 2013 से डिफ़ॉल्ट ज़ूम अब दस्तावेज़ पर सेट नहीं किया जाता, बल्कि यह खुली हुई अंतिम दस्तावेज़ के ज़ूम फ़ैक्टर का उपयोग करता प्रतीत होता है।


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


ज़ूम स्तर को प्रतिशत में निर्दिष्ट करता है। डिफ़ॉल्ट 100 है।
डिफ़ॉल्ट ज़ूम Microsoft Word 2010 तक समर्थित है। Microsoft Word 2013 से डिफ़ॉल्ट ज़ूम अब दस्तावेज़ पर सेट नहीं किया जाता, बल्कि यह खुली हुई अंतिम दस्तावेज़ के ज़ूम फ़ैक्टर का उपयोग करता प्रतीत होता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

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

### getPdfRecognitionMode() {#getPdfRecognitionMode--}
```
public PdfRecognitionMode getPdfRecognitionMode()
```


PDF से रूपांतरण करते समय मान्यता मोड प्राप्त करता है


**Returns:**
[PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode)
### setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode) {#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-}
```
public void setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)
```


PDF से रूपांतरण करते समय मान्यता मोड सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pdfRecognitionMode | [PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode) |  |

### getMarkdownOptions() {#getMarkdownOptions--}
```
public MarkdownOptions getMarkdownOptions()
```


प्राप्त करता है


**Returns:**
[MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions)
### setMarkdownOptions(MarkdownOptions markdownOptions) {#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-}
```
public void setMarkdownOptions(MarkdownOptions markdownOptions)
```


सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| markdownOptions | [MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions) |  |

