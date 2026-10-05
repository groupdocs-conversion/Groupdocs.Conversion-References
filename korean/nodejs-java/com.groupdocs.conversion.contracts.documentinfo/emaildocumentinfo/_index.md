---
title: "EmailDocumentInfo"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Email 문서 메타데이터를 포함합니다"
type: docs
weight: 17
url: /ko/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

Email 문서 메타데이터를 포함합니다
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isSigned()](#isSigned--) | 서명 여부를 가져옵니다 |
| [isEncrypted()](#isEncrypted--) | 암호화 여부를 가져옵니다 |
| [isHtml()](#isHtml--) | HTML 여부를 가져옵니다 |
| [getAttachmentsCount()](#getAttachmentsCount--) | 첨부 파일 수를 가져옵니다 |
| [getAttachmentsNames()](#getAttachmentsNames--) | 첨부 파일 이름을 가져옵니다 |
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메일 | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 크기 | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


서명 여부를 가져옵니다

**Returns:**
boolean - 서명된 경우 true
### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


암호화 여부를 가져옵니다

**Returns:**
boolean - 암호화된 경우 true
### isHtml() {#isHtml--}
```
public boolean isHtml()
```


HTML 여부를 가져옵니다

**Returns:**
boolean - HTML인 경우 true
### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


첨부 파일 수를 가져옵니다

**Returns:**
int - 첨부 파일 수
### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


첨부 파일 이름을 가져옵니다

**Returns:**
java.util.List<java.lang.String> - 첨부 파일 이름
