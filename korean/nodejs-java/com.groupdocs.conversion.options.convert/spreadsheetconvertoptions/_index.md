---
title: "SpreadsheetConvertOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "스프레드시트 파일 형식으로 변환 옵션."
type: docs
weight: 40
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class SpreadsheetConvertOptions extends CommonConvertOptions<SpreadsheetFileType> implements Serializable
```

스프레드시트 파일 형식으로 변환 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | 새로운 [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPassword()](#getPassword--) | 변환된 문서를 비밀번호로 보호하려면 이 속성을 설정하십시오. |
| [setPassword(String value)](#setPassword-java.lang.String-) | 변환된 문서를 비밀번호로 보호하려면 이 속성을 설정하십시오. |
| [getZoom()](#getZoom--) | 줌 레벨을 백분율로 지정합니다. |
| [setZoom(int value)](#setZoom-int-) | 줌 레벨을 백분율로 지정합니다. |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


새로운 [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions) 클래스 인스턴스를 초기화합니다.

### getPassword() {#getPassword--}
```
public final String getPassword()
```


변환된 문서를 비밀번호로 보호하려면 이 속성을 설정하십시오.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


변환된 문서를 비밀번호로 보호하려면 이 속성을 설정하십시오.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


줌 레벨을 백분율로 지정합니다. 기본값은 100입니다.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


줌 레벨을 백분율로 지정합니다. 기본값은 100입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

