---
title: "PdfOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "Pdf फ़ाइल प्रकार में रूपांतरण के विकल्प।"
type: docs
weight: 30
url: /hi/java/com.groupdocs.conversion.options.convert/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptions extends ValueObject implements Serializable
```

Pdf फ़ाइल प्रकार में रूपांतरण के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | ctor |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPdfFormat()](#getPdfFormat--) | रूपांतरित दस्तावेज़ का PDF प्रारूप सेट करता है। |
|
|  | [setPdfFormat(PdfFormats value)](#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-) | रूपांतरित दस्तावेज़ का PDF प्रारूप सेट करता है। |
|
|  | [getRemovePdfACompliance()](#getRemovePdfACompliance--) | PDF-A अनुपालन को हटाता है। |
|
|  | [setRemovePdfACompliance(boolean value)](#setRemovePdfACompliance-boolean-) | PDF-A अनुपालन को हटाता है। |
|
|  | [getZoom()](#getZoom--) | ज़ूम स्तर को प्रतिशत में निर्दिष्ट करता है। |
|
|  | [setZoom(int value)](#setZoom-int-) | ज़ूम स्तर को प्रतिशत में निर्दिष्ट करता है। |
|
|  | [getLinearize()](#getLinearize--) | वेब के लिए PDF दस्तावेज़ को रैखिक बनाता है। |
|
|  | [setLinearize(boolean value)](#setLinearize-boolean-) | वेब के लिए PDF दस्तावेज़ को रैखिक बनाता है। |
|
|  | [getOptimizationOptions()](#getOptimizationOptions--) | PDF अनुकूलन विकल्प |
|
|  | [setOptimizationOptions(PdfOptimizationOptions value)](#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-) | PDF अनुकूलन विकल्प |
|
|  | [getGrayscale()](#getGrayscale--) | PDF को RGB रंगस्थान से ग्रेस्केल में परिवर्तित करें |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | PDF को RGB रंगस्थान से ग्रेस्केल में परिवर्तित करें |
|
|  | [getFormattingOptions()](#getFormattingOptions--) | PDF स्वरूपण विकल्प |
|
|  | [setFormattingOptions(PdfFormattingOptions value)](#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-) | PDF स्वरूपण विकल्प |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | PDF दस्तावेज़ की मेटा जानकारी। |
|
| [setDocumentInfo(PdfDocumentInfo documentInfo)](#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-) |  |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


ctor


### getPdfFormat() {#getPdfFormat--}
```
public final PdfFormats getPdfFormat()
```


रूपांतरित दस्तावेज़ का PDF प्रारूप सेट करता है।


**Returns:**
[PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats)
### setPdfFormat(PdfFormats value) {#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-}
```
public final void setPdfFormat(PdfFormats value)
```


रूपांतरित दस्तावेज़ का PDF प्रारूप सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats) |  |

### getRemovePdfACompliance() {#getRemovePdfACompliance--}
```
public final boolean getRemovePdfACompliance()
```


PDF-A अनुपालन को हटाता है।


**Returns:**
बूलियन
### setRemovePdfACompliance(boolean value) {#setRemovePdfACompliance-boolean-}
```
public final void setRemovePdfACompliance(boolean value)
```


PDF-A अनुपालन को हटाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


ज़ूम स्तर को प्रतिशत में निर्दिष्ट करता है। डिफ़ॉल्ट 100 है।


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


ज़ूम स्तर को प्रतिशत में निर्दिष्ट करता है। डिफ़ॉल्ट 100 है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getLinearize() {#getLinearize--}
```
public final boolean getLinearize()
```


वेब के लिए PDF दस्तावेज़ को रैखिक बनाता है।


**Returns:**
बूलियन
### setLinearize(boolean value) {#setLinearize-boolean-}
```
public final void setLinearize(boolean value)
```


वेब के लिए PDF दस्तावेज़ को रैखिक बनाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getOptimizationOptions() {#getOptimizationOptions--}
```
public final PdfOptimizationOptions getOptimizationOptions()
```


PDF अनुकूलन विकल्प


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions)
### setOptimizationOptions(PdfOptimizationOptions value) {#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-}
```
public final void setOptimizationOptions(PdfOptimizationOptions value)
```


PDF अनुकूलन विकल्प


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


PDF को RGB रंगस्थान से ग्रेस्केल में परिवर्तित करें


**Returns:**
बूलियन
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


PDF को RGB रंगस्थान से ग्रेस्केल में परिवर्तित करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public final PdfFormattingOptions getFormattingOptions()
```


PDF स्वरूपण विकल्प


**Returns:**
[PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions)
### setFormattingOptions(PdfFormattingOptions value) {#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-}
```
public final void setFormattingOptions(PdfFormattingOptions value)
```


PDF स्वरूपण विकल्प


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public PdfDocumentInfo getDocumentInfo()
```


PDF दस्तावेज़ की मेटा जानकारी।


**Returns:**
[PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo)
### setDocumentInfo(PdfDocumentInfo documentInfo) {#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-}
```
public void setDocumentInfo(PdfDocumentInfo documentInfo)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| documentInfo | [PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo) |  |

