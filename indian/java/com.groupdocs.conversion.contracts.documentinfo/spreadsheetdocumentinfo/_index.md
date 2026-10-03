---
title: "SpreadsheetDocumentInfo"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "Spreadsheet दस्तावेज़ मेटाडेटा शामिल है"
type: docs
weight: 36
url: /hi/java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

Spreadsheet दस्तावेज़ मेटाडेटा शामिल है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getTitle()](#getTitle--) | शीर्षक प्राप्त करता है |
|
|  | [getWorksheetsCount()](#getWorksheetsCount--) | वर्कशीट्स की गिनती प्राप्त करता है |
|
|  | [getAuthor()](#getAuthor--) | लेखक प्राप्त करता है |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | जाँचता है कि दस्तावेज़ पासवर्ड संरक्षित है या नहीं |
|
|  | [getWorksheets()](#getWorksheets--) | वर्कशीट्स के नाम |
|
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्प्रेडशीट | com.aspose.cells.Workbook |  |
| isPasswordProtected | बूलियन |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| आकार | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


शीर्षक प्राप्त करता है


**Returns:**
java.lang.String - शीर्षक

### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


वर्कशीट्स की गिनती प्राप्त करता है


**Returns:**
int - वर्कशीट्स की गिनती

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
boolean - सही यदि दस्तावेज़ पासवर्ड संरक्षित है

### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


वर्कशीट्स के नाम


**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| वर्कशीट्स | java.util.List<java.lang.String> |  |

