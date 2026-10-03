---
title: "DjVuDocumentInfo"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "DjVu दस्तावेज़ मेटाडेटा शामिल है"
type: docs
weight: 15
url: /hi/java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo), [com.groupdocs.conversion.contracts.documentinfo.ImageDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/imagedocumentinfo)
```
public class DjVuDocumentInfo extends ImageDocumentInfo
```

DjVu दस्तावेज़ मेटाडेटा शामिल है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [DjVuDocumentInfo(DjvuImage image, FileType format, long size)](#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getVerticalResolution()](#getVerticalResolution--) | ऊर्ध्वाधर रिज़ॉल्यूशन प्राप्त करता है |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | क्षैतिज रिज़ॉल्यूशन प्राप्त करें |
|
|  | [getOpacity()](#getOpacity--) | छवि अपारदर्शिता प्राप्त करता है |
|
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| छवि | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| आकार | long |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


ऊर्ध्वाधर रिज़ॉल्यूशन प्राप्त करता है


**Returns:**
double - ऊर्ध्वाधर रिज़ॉल्यूशन

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


क्षैतिज रिज़ॉल्यूशन प्राप्त करें


**Returns:**
double - क्षैतिज रिज़ॉल्यूशन

### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


छवि अपारदर्शिता प्राप्त करता है


**Returns:**
float - छवि अपारदर्शिता

