---
title: "DatabaseLoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "데이터베이스 문서 불러오기 옵션."
type: docs
weight: 15
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/databaseloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
```
public class DatabaseLoadOptions extends LoadOptions
```

데이터베이스 문서 불러오기 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DatabaseLoadOptions()](#DatabaseLoadOptions--) |   클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) | 입력 문서 파일 형식을 가져옵니다. |
| [setFormat(DatabaseFileType format)](#setFormat-com.groupdocs.conversion.filetypes.DatabaseFileType-) | 입력 문서 파일 형식을 설정합니다. |
### DatabaseLoadOptions() {#DatabaseLoadOptions--}
```
public DatabaseLoadOptions()
```


  클래스의 새 인스턴스를 초기화합니다.

### getFormat() {#getFormat--}
```
public DatabaseFileType getFormat()
```


입력 문서 파일 형식을 가져옵니다.

**Returns:**
[DatabaseFileType](../../com.groupdocs.conversion.filetypes/databasefiletype)
### setFormat(DatabaseFileType format) {#setFormat-com.groupdocs.conversion.filetypes.DatabaseFileType-}
```
public void setFormat(DatabaseFileType format)
```


입력 문서 파일 형식을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| format | [DatabaseFileType](../../com.groupdocs.conversion.filetypes/databasefiletype) |  |

