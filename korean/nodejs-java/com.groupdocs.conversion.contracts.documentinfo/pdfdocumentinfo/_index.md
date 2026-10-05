---
title: "PdfDocumentInfo"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Pdf 문서 메타데이터 포함"
type: docs
weight: 31
url: /ko/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/pdfdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PdfDocumentInfo extends DocumentInfo
```

Pdf 문서 메타데이터 포함
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PdfDocumentInfo(Document pdf, FileType format, long size)](#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) | 버전을 가져옵니다 |
| [getTitle()](#getTitle--) | 제목을 가져옵니다 |
| [getAuthor()](#getAuthor--) | 작성자를 가져옵니다 |
| [isPasswordProtected()](#isPasswordProtected--) | 암호화 여부를 가져옵니다 |
| [isLandscape()](#isLandscape--) | 페이지가 가로 방향인지 여부를 가져옵니다 |
| [getHeight()](#getHeight--) | 페이지 높이를 가져옵니다 |
| [getWidth()](#getWidth--) | 페이지 너비를 가져옵니다 |
| [getTableOfContents()](#getTableOfContents--) | 목차를 가져옵니다 |
| [setTableOfContents(List<TableOfContentsItem> tableOfContents)](#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--) | 목차를 설정합니다 |
### PdfDocumentInfo(Document pdf, FileType format, long size) {#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PdfDocumentInfo(Document pdf, FileType format, long size)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pdf | com.aspose.pdf.Document |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 크기 | long |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


버전을 가져옵니다

**Returns:**
java.lang.String - 버전
### getTitle() {#getTitle--}
```
public String getTitle()
```


제목을 가져옵니다

**Returns:**
java.lang.String - 제목
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


암호화 여부를 가져옵니다

**Returns:**
boolean - 암호화된 경우 true
### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


페이지가 가로 방향인지 여부를 가져옵니다

**Returns:**
boolean - 페이지가 가로 방향인 경우 true
### getHeight() {#getHeight--}
```
public double getHeight()
```


페이지 높이를 가져옵니다

**Returns:**
double - 페이지 높이
### getWidth() {#getWidth--}
```
public double getWidth()
```


페이지 너비를 가져옵니다

**Returns:**
double - 페이지 너비
### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


목차를 가져옵니다

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - 목차
### setTableOfContents(List<TableOfContentsItem> tableOfContents) {#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--}
```
public void setTableOfContents(List<TableOfContentsItem> tableOfContents)
```


목차를 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| tableOfContents | java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> | 목차 |

