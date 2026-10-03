---
title: "PresentationDocumentInfo"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "Presentation दस्तावेज़ मेटाडेटा शामिल है"
type: docs
weight: 31
url: /hi/java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

Presentation दस्तावेज़ मेटाडेटा शामिल है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getTitle()](#getTitle--) | शीर्षक प्राप्त करता है |
|
|  | [setTitle(String title)](#setTitle-java.lang.String-) | शीर्षक सेट करता है |
|
|  | [getAuthor()](#getAuthor--) | लेखक प्राप्त करता है |
|
|  | [setAuthor(String author)](#setAuthor-java.lang.String-) | लेखक सेट करता है |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | प्राप्त करता है कि दस्तावेज़ पासवर्ड से सुरक्षित है |
|
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रस्तुति | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| आकार | long |  |
| isPasswordProtected | बूलियन |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


शीर्षक प्राप्त करता है


**Returns:**
java.lang.String - शीर्षक

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


शीर्षक सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | शीर्षक | java.lang.String | शीर्षक |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


लेखक प्राप्त करता है


**Returns:**
java.lang.String - लेखक

### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


लेखक सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | लेखक | java.lang.String | लेखक |
|

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


प्राप्त करता है कि दस्तावेज़ पासवर्ड से सुरक्षित है


**Returns:**
boolean - `true` यदि दस्तावेज़ पासवर्ड से सुरक्षित है

