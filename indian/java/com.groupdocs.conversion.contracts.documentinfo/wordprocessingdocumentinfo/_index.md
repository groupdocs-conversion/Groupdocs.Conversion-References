---
title: "WordProcessingDocumentInfo"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "Wordprocessing दस्तावेज़ मेटाडेटा शामिल है"
type: docs
weight: 45
url: /hi/java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

Wordprocessing दस्तावेज़ मेटाडेटा शामिल है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getWords()](#getWords--) | शब्दों की गिनती प्राप्त करता है |
|
|  | [getLines()](#getLines--) | पंक्तियों की गिनती प्राप्त करता है |
|
|  | [getTitle()](#getTitle--) | शीर्षक प्राप्त करता है |
|
|  | [getAuthor()](#getAuthor--) | लेखक प्राप्त करता है |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | जाँचता है कि दस्तावेज़ पासवर्ड संरक्षित है या नहीं |
|
|  | [getTableOfContents()](#getTableOfContents--) | सामग्री तालिका |
|
### WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size) {#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| wordprocessing | com.aspose.words.Document |  |
| isPasswordProtected | बूलियन |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| आकार | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


शब्दों की गिनती प्राप्त करता है


**Returns:**
int - शब्दों की गिनती

### getLines() {#getLines--}
```
public int getLines()
```


पंक्तियों की गिनती प्राप्त करता है


**Returns:**
int - पंक्तियों की गिनती

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


जाँचता है कि दस्तावेज़ पासवर्ड संरक्षित है या नहीं


**Returns:**
boolean - `true` यदि दस्तावेज़ पासवर्ड से सुरक्षित है

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


सामग्री तालिका


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - सामग्री तालिका

