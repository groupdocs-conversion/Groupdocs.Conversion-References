---
title: "PdfDocumentInfo"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "PDF दस्तावेज़ मेटाडेटा शामिल है"
type: docs
weight: 28
url: /hi/java/com.groupdocs.conversion.contracts.documentinfo/pdfdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PdfDocumentInfo extends DocumentInfo
```

PDF दस्तावेज़ मेटाडेटा शामिल है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PdfDocumentInfo(Document pdf, FileType format, long size)](#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getVersion()](#getVersion--) | प्राप्त करता है संस्करण |
|
|  | [getTitle()](#getTitle--) | शीर्षक प्राप्त करता है |
|
|  | [getAuthor()](#getAuthor--) | लेखक प्राप्त करता है |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | प्राप्त करता है एन्क्रिप्टेड है |
|
|  | [isLandscape()](#isLandscape--) | प्राप्त करता है पृष्ठ लैंडस्केप्ड है |
|
|  | [getHeight()](#getHeight--) | प्राप्त करता है पृष्ठ की ऊँचाई |
|
|  | [getWidth()](#getWidth--) | प्राप्त करता है पृष्ठ की चौड़ाई |
|
|  | [getTableOfContents()](#getTableOfContents--) | प्राप्त करता है सामग्री तालिका |
|
|  | [setTableOfContents(List<TableOfContentsItem> tableOfContents)](#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--) | सेट करता है सामग्री तालिका |
|
### PdfDocumentInfo(Document pdf, FileType format, long size) {#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PdfDocumentInfo(Document pdf, FileType format, long size)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pdf | com.aspose.pdf.Document |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| आकार | long |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


प्राप्त करता है संस्करण


**Returns:**
java.lang.String - संस्करण

### getTitle() {#getTitle--}
```
public String getTitle()
```


शीर्षक प्राप्त करता है


**Returns:**
java.lang.String - शीर्षक

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


लेखक प्राप्त करता है


**Returns:**
java.lang.String - लेखक

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


प्राप्त करता है एन्क्रिप्टेड है


**Returns:**
boolean - यदि एन्क्रिप्टेड हो तो true

### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


प्राप्त करता है पृष्ठ लैंडस्केप्ड है


**Returns:**
boolean - यदि पृष्ठ लैंडस्केप्ड हो तो true

### getHeight() {#getHeight--}
```
public double getHeight()
```


प्राप्त करता है पृष्ठ की ऊँचाई


**Returns:**
double - पृष्ठ की ऊँचाई

### getWidth() {#getWidth--}
```
public double getWidth()
```


प्राप्त करता है पृष्ठ की चौड़ाई


**Returns:**
double - पृष्ठ की चौड़ाई

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


प्राप्त करता है सामग्री तालिका


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - सामग्री तालिका

### setTableOfContents(List<TableOfContentsItem> tableOfContents) {#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--}
```
public void setTableOfContents(List<TableOfContentsItem> tableOfContents)
```


सेट करता है सामग्री तालिका


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | tableOfContents | java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> | सामग्री तालिका |
|

