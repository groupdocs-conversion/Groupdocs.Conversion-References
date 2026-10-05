---
title: "PresentationDocumentInfo"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Presentation 문서 메타데이터 포함"
type: docs
weight: 34
url: /ko/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

Presentation 문서 메타데이터 포함
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTitle()](#getTitle--) | 제목을 가져옵니다 |
| [setTitle(String title)](#setTitle-java.lang.String-) | 제목을 설정합니다 |
| [getAuthor()](#getAuthor--) | 작성자를 가져옵니다 |
| [setAuthor(String author)](#setAuthor-java.lang.String-) | 작성자를 설정합니다 |
| [isPasswordProtected()](#isPasswordProtected--) | 문서 비밀번호 보호 여부를 가져옵니다 |
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 프레젠테이션 | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 크기 | long |  |
| isPasswordProtected | boolean |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


제목을 가져옵니다

**Returns:**
java.lang.String - 제목
### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


제목을 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 제목 | java.lang.String | 제목 |

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


작성자를 가져옵니다

**Returns:**
java.lang.String - 작성자
### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


작성자를 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 작성자 | java.lang.String | 작성자 |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


문서 비밀번호 보호 여부를 가져옵니다

**Returns:**
boolean - `true` if 문서가 암호로 보호된 경우
