---
title: "PdfFormattingOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "Pdf फ़ॉर्मैटिंग विकल्पों को परिभाषित करता है।"
type: docs
weight: 28
url: /hi/java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

Pdf फ़ॉर्मैटिंग विकल्पों को परिभाषित करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getCenterWindow()](#getCenterWindow--) | निर्दिष्ट करता है कि दस्तावेज़ की विंडो की स्थिति स्क्रीन पर केंद्रित होगी या नहीं। |
|
|  | [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | निर्दिष्ट करता है कि दस्तावेज़ की विंडो की स्थिति स्क्रीन पर केंद्रित होगी या नहीं। |
|
|  | [getDirection()](#getDirection--) | पाठ का पढ़ने क्रम सेट करता है: L2R (बाएँ से दाएँ) या R2L (दाएँ से बाएँ)। |
|
|  | [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | पाठ का पढ़ने क्रम सेट करता है: L2R (बाएँ से दाएँ) या R2L (दाएँ से बाएँ)। |
|
|  | [getDisplayDocTitle()](#getDisplayDocTitle--) | निर्दिष्ट करता है कि दस्तावेज़ की विंडो शीर्षक बार में दस्तावेज़ शीर्षक दिखाया जाना चाहिए या नहीं। |
|
|  | [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | निर्दिष्ट करता है कि दस्तावेज़ की विंडो शीर्षक बार में दस्तावेज़ शीर्षक दिखाया जाना चाहिए या नहीं। |
|
|  | [getFitWindow()](#getFitWindow--) | निर्दिष्ट करता है कि दस्तावेज़ विंडो को पहली प्रदर्शित पृष्ठ में फिट होने के लिए आकार बदलना चाहिए या नहीं। |
|
|  | [setFitWindow(boolean value)](#setFitWindow-boolean-) | निर्दिष्ट करता है कि दस्तावेज़ विंडो को पहली प्रदर्शित पृष्ठ में फिट होने के लिए आकार बदलना चाहिए या नहीं। |
|
|  | [getHideMenuBar()](#getHideMenuBar--) | निर्दिष्ट करता है कि दस्तावेज़ सक्रिय होने पर मेनू बार को छिपाया जाना चाहिए या नहीं। |
|
|  | [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | निर्दिष्ट करता है कि दस्तावेज़ सक्रिय होने पर मेनू बार को छिपाया जाना चाहिए या नहीं। |
|
|  | [getHideToolBar()](#getHideToolBar--) | निर्दिष्ट करता है कि दस्तावेज़ सक्रिय होने पर टूलबार को छिपाया जाना चाहिए या नहीं। |
|
|  | [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | निर्दिष्ट करता है कि दस्तावेज़ सक्रिय होने पर टूलबार को छिपाया जाना चाहिए या नहीं। |
|
|  | [getHideWindowUI()](#getHideWindowUI--) | निर्दिष्ट करता है कि दस्तावेज़ सक्रिय होने पर उपयोगकर्ता इंटरफ़ेस तत्वों को छिपाया जाना चाहिए या नहीं। |
|
|  | [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | निर्दिष्ट करता है कि दस्तावेज़ सक्रिय होने पर उपयोगकर्ता इंटरफ़ेस तत्वों को छिपाया जाना चाहिए या नहीं। |
|
|  | [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | पेज मोड सेट करता है, यह निर्दिष्ट करता है कि पूर्ण-स्क्रीन मोड से बाहर निकलते समय दस्तावेज़ को कैसे प्रदर्शित किया जाए। |
|
|  | [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | पेज मोड सेट करता है, यह निर्दिष्ट करता है कि पूर्ण-स्क्रीन मोड से बाहर निकलते समय दस्तावेज़ को कैसे प्रदर्शित किया जाए। |
|
|  | [getPageLayout()](#getPageLayout--) | पेज लेआउट सेट करता है जो दस्तावेज़ खोलते समय उपयोग किया जाएगा। |
|
|  | [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | पेज लेआउट सेट करता है जो दस्तावेज़ खोलते समय उपयोग किया जाएगा। |
|
|  | [getPageMode()](#getPageMode--) | पेज मोड सेट करता है, यह निर्दिष्ट करता है कि दस्तावेज़ खोलते समय कैसे प्रदर्शित किया जाए। |
|
|  | [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | पेज मोड सेट करता है, यह निर्दिष्ट करता है कि दस्तावेज़ खोलते समय कैसे प्रदर्शित किया जाए। |
|
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


निर्दिष्ट करता है कि दस्तावेज़ की विंडो की स्थिति स्क्रीन पर केंद्रित होगी या नहीं। डिफ़ॉल्ट: false.


**Returns:**
बूलियन
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


निर्दिष्ट करता है कि दस्तावेज़ की विंडो की स्थिति स्क्रीन पर केंद्रित होगी या नहीं। डिफ़ॉल्ट: false.


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


पाठ का पढ़ने क्रम सेट करता है: L2R (बाएँ से दाएँ) या R2L (दाएँ से बाएँ)। डिफ़ॉल्ट: L2R.


**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


पाठ का पढ़ने क्रम सेट करता है: L2R (बाएँ से दाएँ) या R2L (दाएँ से बाएँ)। डिफ़ॉल्ट: L2R.


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


निर्दिष्ट करता है कि दस्तावेज़ की विंडो शीर्षक बार में दस्तावेज़ शीर्षक दिखाया जाना चाहिए या नहीं। डिफ़ॉल्ट: false.


**Returns:**
बूलियन
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


निर्दिष्ट करता है कि दस्तावेज़ की विंडो शीर्षक बार में दस्तावेज़ शीर्षक दिखाया जाना चाहिए या नहीं। डिफ़ॉल्ट: false.


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


निर्दिष्ट करता है कि दस्तावेज़ विंडो को पहली प्रदर्शित पृष्ठ में फिट होने के लिए आकार बदलना चाहिए या नहीं। डिफ़ॉल्ट: false.


**Returns:**
बूलियन
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


निर्दिष्ट करता है कि दस्तावेज़ विंडो को पहली प्रदर्शित पृष्ठ में फिट होने के लिए आकार बदलना चाहिए या नहीं। डिफ़ॉल्ट: false.


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


निर्दिष्ट करता है कि दस्तावेज़ सक्रिय होने पर मेनू बार को छिपाया जाना चाहिए या नहीं। डिफ़ॉल्ट: false.


**Returns:**
बूलियन
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


निर्दिष्ट करता है कि दस्तावेज़ सक्रिय होने पर मेनू बार को छिपाया जाना चाहिए या नहीं। डिफ़ॉल्ट: false.


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


निर्दिष्ट करता है कि दस्तावेज़ सक्रिय होने पर टूलबार को छिपाया जाना चाहिए या नहीं। डिफ़ॉल्ट: false.


**Returns:**
बूलियन
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


निर्दिष्ट करता है कि दस्तावेज़ सक्रिय होने पर टूलबार को छिपाया जाना चाहिए या नहीं। डिफ़ॉल्ट: false.


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


निर्दिष्ट करता है कि दस्तावेज़ सक्रिय होने पर उपयोगकर्ता इंटरफ़ेस तत्वों को छिपाया जाना चाहिए या नहीं। डिफ़ॉल्ट: false.


**Returns:**
बूलियन
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


निर्दिष्ट करता है कि दस्तावेज़ सक्रिय होने पर उपयोगकर्ता इंटरफ़ेस तत्वों को छिपाया जाना चाहिए या नहीं। डिफ़ॉल्ट: false.


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


पेज मोड सेट करता है, यह निर्दिष्ट करता है कि पूर्ण-स्क्रीन मोड से बाहर निकलते समय दस्तावेज़ को कैसे प्रदर्शित किया जाए।


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


पेज मोड सेट करता है, यह निर्दिष्ट करता है कि पूर्ण-स्क्रीन मोड से बाहर निकलते समय दस्तावेज़ को कैसे प्रदर्शित किया जाए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


पेज लेआउट सेट करता है जो दस्तावेज़ खोलते समय उपयोग किया जाएगा।


**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


पेज लेआउट सेट करता है जो दस्तावेज़ खोलते समय उपयोग किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


पेज मोड सेट करता है, यह निर्दिष्ट करता है कि दस्तावेज़ खोलते समय कैसे प्रदर्शित किया जाए।


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


पेज मोड सेट करता है, यह निर्दिष्ट करता है कि दस्तावेज़ खोलते समय कैसे प्रदर्शित किया जाए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

