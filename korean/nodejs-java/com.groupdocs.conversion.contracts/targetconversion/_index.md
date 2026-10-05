---
title: "TargetConversion"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "가능한 대상 변환과 그것이 기본인지 보조인지를 나타내는 플래그를 나타냅니다"
type: docs
weight: 14
url: /ko/nodejs-java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

가능한 대상 변환과 그것이 기본인지 보조인지를 나타내는 플래그를 나타냅니다
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) | 대상 문서 형식 |
| [isPrimary()](#isPrimary--) | 변환이 기본인지 여부 |
| [getConvertOptions()](#getConvertOptions--) | 현재 유형으로 변환하는 데 사용할 수 있는 미리 정의된 변환 옵션 |
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


대상 문서 형식

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format
### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


변환이 기본인지 여부

**Returns:**
boolean - 기본인 경우 `true`
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


현재 유형으로 변환하는 데 사용할 수 있는 미리 정의된 변환 옵션

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options
