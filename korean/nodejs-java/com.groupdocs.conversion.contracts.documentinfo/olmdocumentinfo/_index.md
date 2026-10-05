---
title: "OlmDocumentInfo"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "olm 문서 메타데이터 포함"
type: docs
weight: 27
url: /ko/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/olmdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class OlmDocumentInfo extends DocumentInfo
```

olm 문서 메타데이터 포함
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OlmDocumentInfo(OlmStorage storage, long size)](#OlmDocumentInfo-com.aspose.email.OlmStorage-long-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFolders()](#getFolders--) | 스토리지의 폴더 |
### OlmDocumentInfo(OlmStorage storage, long size) {#OlmDocumentInfo-com.aspose.email.OlmStorage-long-}
```
public OlmDocumentInfo(OlmStorage storage, long size)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스토리지 | com.aspose.email.OlmStorage |  |
| 크기 | long |  |

### getFolders() {#getFolders--}
```
public List<OlmFolderInfo> getFolders()
```


스토리지의 폴더

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.OlmFolderInfo>
