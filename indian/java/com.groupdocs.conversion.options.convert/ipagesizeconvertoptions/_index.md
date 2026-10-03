---
title: "IPageSizeConvertOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "पेज साइज का समर्थन करने वाले रूपांतरण विकल्पों का प्रतिनिधित्व करता है"
type: docs
weight: 54
url: /hi/java/com.groupdocs.conversion.options.convert/ipagesizeconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageSizeConvertOptions extends IConvertOptions
```

पेज साइज का समर्थन करने वाले रूपांतरण विकल्पों का प्रतिनिधित्व करता है

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | रूपांतरण के बाद वांछित पृष्ठ आकार प्राप्त करता है |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) | रूपांतरण के बाद वांछित पृष्ठ आकार सेट करें |
|
|  | [getPageWidth()](#getPageWidth--) | यदि PageSize.Custom पर सेट है तो बिंदुओं में निर्दिष्ट पृष्ठ चौड़ाई |
|
|  | [setPageWidth(float pageWidth)](#setPageWidth-float-) | वांछित पृष्ठ चौड़ाई सेट करें |
|
|  | [getPageHeight()](#getPageHeight--) | यदि PageSize.Custom पर सेट है तो बिंदुओं में निर्दिष्ट पृष्ठ ऊँचाई |
|
|  | [setPageHeight(float pageHeight)](#setPageHeight-float-) | वांछित पृष्ठ ऊँचाई सेट करें |
|
### getPageSize() {#getPageSize--}
```
public abstract PageSize getPageSize()
```


रूपांतरण के बाद वांछित पृष्ठ आकार प्राप्त करता है


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public abstract void setPageSize(PageSize pageSize)
```


रूपांतरण के बाद वांछित पृष्ठ आकार सेट करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


यदि PageSize.Custom पर सेट है तो बिंदुओं में निर्दिष्ट पृष्ठ चौड़ाई


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public abstract void setPageWidth(float pageWidth)
```


वांछित पृष्ठ चौड़ाई सेट करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


यदि PageSize.Custom पर सेट है तो बिंदुओं में निर्दिष्ट पृष्ठ ऊँचाई


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public abstract void setPageHeight(float pageHeight)
```


वांछित पृष्ठ ऊँचाई सेट करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageHeight | float |  |

