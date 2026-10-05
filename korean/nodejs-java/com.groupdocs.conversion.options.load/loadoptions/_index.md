---
title: "LoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "문서 로드 옵션 추상 클래스."
type: docs
weight: 25
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public abstract class LoadOptions extends ValueObject implements Serializable
```

문서 로드 옵션 추상 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) | 입력 문서 파일 유형 |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | 입력 문서 파일 유형 |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getFormat() {#getFormat--}
```
public FileType getFormat()
```


입력 문서 파일 유형

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


입력 문서 파일 유형

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

