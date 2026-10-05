---
title: "RtfOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "RTF 파일 형식으로 변환 옵션."
type: docs
weight: 39
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/rtfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class RtfOptions extends ValueObject implements Serializable
```

RTF 파일 형식으로 변환 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RtfOptions()](#RtfOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getExportImagesForOldReaders()](#getExportImagesForOldReaders--) | 키워드가 "old readers"용으로 RTF에 기록되는지 여부를 지정합니다. |
| [setExportImagesForOldReaders(boolean value)](#setExportImagesForOldReaders-boolean-) | 키워드가 "old readers"용으로 RTF에 기록되는지 여부를 지정합니다. |
### RtfOptions() {#RtfOptions--}
```
public RtfOptions()
```


### getExportImagesForOldReaders() {#getExportImagesForOldReaders--}
```
public final boolean getExportImagesForOldReaders()
```


키워드가 "old readers"용으로 RTF에 기록되는지 여부를 지정합니다. 이는 RTF 문서의 크기에 크게 영향을 줄 수 있습니다. 기본값은 False입니다.

**Returns:**
boolean
### setExportImagesForOldReaders(boolean value) {#setExportImagesForOldReaders-boolean-}
```
public final void setExportImagesForOldReaders(boolean value)
```


키워드가 "old readers"용으로 RTF에 기록되는지 여부를 지정합니다. 이는 RTF 문서의 크기에 크게 영향을 줄 수 있습니다. 기본값은 False입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

