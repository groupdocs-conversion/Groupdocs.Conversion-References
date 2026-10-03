---
title: "CadDocumentInfo"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "CAD दस्तावेज़ मेटाडेटा शामिल है"
type: docs
weight: 11
url: /hi/java/com.groupdocs.conversion.contracts.documentinfo/caddocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class CadDocumentInfo extends DocumentInfo
```

CAD दस्तावेज़ मेटाडेटा शामिल है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [CadDocumentInfo(Image cad, FileType format, long size)](#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getWidth()](#getWidth--) | चौड़ाई |
|
|  | [getHeight()](#getHeight--) | ऊँचाई |
|
|  | [getLayouts()](#getLayouts--) | दस्तावेज़ में लेआउट |
|
|  | [getLayers()](#getLayers--) | दस्तावेज़ में लेयर |
|
### CadDocumentInfo(Image cad, FileType format, long size) {#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public CadDocumentInfo(Image cad, FileType format, long size)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cad | com.aspose.cad.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| आकार | long |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


चौड़ाई


**Returns:**
int - चौड़ाई

### getHeight() {#getHeight--}
```
public int getHeight()
```


ऊँचाई


**Returns:**
int - ऊँचाई

### getLayouts() {#getLayouts--}
```
public List<String> getLayouts()
```


दस्तावेज़ में लेआउट


**Returns:**
java.util.List<java.lang.String> - दस्तावेज़ में लेआउट

### getLayers() {#getLayers--}
```
public List<String> getLayers()
```


दस्तावेज़ में लेयर


**Returns:**
java.util.List<java.lang.String> - दस्तावेज़ में लेयर

