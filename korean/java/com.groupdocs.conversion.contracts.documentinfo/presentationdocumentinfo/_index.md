---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "프레젠테이션 문서 메타데이터를 포함합니다"
type: docs
weight: 31
url: /ko/java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

프레젠테이션 문서 메타데이터를 포함합니다

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getTitle()](#getTitle--) | 제목을 가져옵니다 |
|
|  | [setTitle(String title)](#setTitle-java.lang.String-) | 제목을 설정합니다 |
|
|  | [getAuthor()](#getAuthor--) | 작성자를 가져옵니다 |
|
|  | [setAuthor(String author)](#setAuthor-java.lang.String-) | 작성자를 설정합니다 |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | 문서가 비밀번호로 보호되는지 가져옵니다 |
|
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 프레젠테이션 | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |
| isPasswordProtected | 불리언 |  |

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
|  | 제목 | java.lang.String | 제목 |
|

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
|  | 작성자 | java.lang.String | 작성자 |
|

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


문서가 비밀번호로 보호되는지 가져옵니다


**Returns:**
boolean - 문서가 비밀번호로 보호되는 경우 `true`

