---
title: "SpreadsheetDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحتوي على بيانات تعريف مستند جدول البيانات"
type: docs
weight: 36
url: /ar/java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

يحتوي على بيانات تعريف مستند جدول البيانات

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getTitle()](#getTitle--) | يحصل على العنوان |
|
|  | [getWorksheetsCount()](#getWorksheetsCount--) | يحصل على عدد أوراق العمل |
|
|  | [getAuthor()](#getAuthor--) | يحصل على المؤلف |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | يحصل على ما إذا كان المستند محميًا بكلمة مرور |
|
|  | [getWorksheets()](#getWorksheets--) | أسماء أوراق العمل |
|
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| جدول بيانات | com.aspose.cells.Workbook |  |
| isPasswordProtected | منطقي |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


يحصل على العنوان


**Returns:**
java.lang.String - العنوان

### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


يحصل على عدد أوراق العمل


**Returns:**
int - عدد أوراق العمل

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


يحصل على المؤلف


**Returns:**
java.lang.String - المؤلف

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


يحصل على ما إذا كان المستند محميًا بكلمة مرور


**Returns:**
boolean - true إذا كان المستند محميًا بكلمة مرور

### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


أسماء أوراق العمل


**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| أوراق العمل | java.util.List<java.lang.String> |  |

