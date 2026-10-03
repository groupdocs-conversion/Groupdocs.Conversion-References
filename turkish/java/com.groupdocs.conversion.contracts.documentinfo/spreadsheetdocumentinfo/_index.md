---
title: "SpreadsheetDocumentInfo"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Spreadsheet belgesi üst verilerini içerir"
type: docs
weight: 36
url: /tr/java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

Spreadsheet belgesi üst verilerini içerir

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getTitle()](#getTitle--) | Başlığı alır |
|
|  | [getWorksheetsCount()](#getWorksheetsCount--) | Çalışma sayfalarının sayısını alır |
|
|  | [getAuthor()](#getAuthor--) | Yazarı alır |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Belgenin şifre korumalı olup olmadığını alır |
|
|  | [getWorksheets()](#getWorksheets--) | Çalışma sayfası adları |
|
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| elektronik tablo | com.aspose.cells.Workbook |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Başlığı alır


**Returns:**
java.lang.String - başlık

### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


Çalışma sayfalarının sayısını alır


**Returns:**
int - çalışma sayfaları sayısı

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Yazarı alır


**Returns:**
java.lang.String - yazar

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Belgenin şifre korumalı olup olmadığını alır


**Returns:**
boolean - belge şifre korumalıysa doğru

### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


Çalışma sayfası adları


**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çalışma sayfaları | java.util.List<java.lang.String> |  |

