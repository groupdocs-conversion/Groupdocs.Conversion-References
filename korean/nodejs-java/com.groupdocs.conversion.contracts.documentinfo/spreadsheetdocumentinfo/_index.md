---
title: "SpreadsheetDocumentInfo"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Spreadsheet 문서 메타데이터 포함"
type: docs
weight: 39
url: /ko/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

Spreadsheet 문서 메타데이터 포함
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTitle()](#getTitle--) | 제목을 가져옵니다 |
| [getWorksheetsCount()](#getWorksheetsCount--) | 워크시트 수를 가져옵니다 |
| [getAuthor()](#getAuthor--) | 작성자를 가져옵니다 |
| [isPasswordProtected()](#isPasswordProtected--) | 문서가 비밀번호로 보호되는지 여부를 가져옵니다 |
| [getWorksheets()](#getWorksheets--) | 워크시트 이름 |
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스프레드시트 | com.aspose.cells.Workbook |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 크기 | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


제목을 가져옵니다

**Returns:**
java.lang.String - 제목
### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


워크시트 수를 가져옵니다

**Returns:**
int - 워크시트 수
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


작성자를 가져옵니다

**Returns:**
java.lang.String - 작성자
### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


문서가 비밀번호로 보호되는지 여부를 가져옵니다

**Returns:**
boolean - 문서가 비밀번호로 보호되는 경우 true
### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


워크시트 이름

**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheets | java.util.List<java.lang.String> |  |

