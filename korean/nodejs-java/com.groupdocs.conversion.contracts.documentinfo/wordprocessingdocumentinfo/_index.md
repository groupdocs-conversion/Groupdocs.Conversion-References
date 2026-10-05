---
title: "WordProcessingDocumentInfo"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Wordprocessing 문서 메타데이터를 포함합니다"
type: docs
weight: 48
url: /ko/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

Wordprocessing 문서 메타데이터를 포함합니다
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWords()](#getWords--) | 단어 수를 가져옵니다 |
| [getLines()](#getLines--) | 줄 수를 가져옵니다 |
| [getTitle()](#getTitle--) | 제목을 가져옵니다 |
| [getAuthor()](#getAuthor--) | 작성자를 가져옵니다 |
| [isPasswordProtected()](#isPasswordProtected--) | 문서가 비밀번호로 보호되는지 여부를 가져옵니다 |
| [getTableOfContents()](#getTableOfContents--) | 목차 |
### WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size) {#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| wordprocessing | com.aspose.words.Document |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 크기 | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


단어 수를 가져옵니다

**Returns:**
int - 단어 수
### getLines() {#getLines--}
```
public int getLines()
```


줄 수를 가져옵니다

**Returns:**
int - 줄 수
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


문서가 비밀번호로 보호되는지 여부를 가져옵니다

**Returns:**
boolean - `true` if 문서가 암호로 보호된 경우
### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


목차

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - 목차
