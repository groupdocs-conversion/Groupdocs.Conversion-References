---
title: "PresentationConvertOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "프레젠테이션 파일 형식으로 변환 옵션을 설명합니다."
type: docs
weight: 33
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class PresentationConvertOptions extends CommonConvertOptions<PresentationFileType> implements Serializable
```

프레젠테이션 파일 형식으로 변환 옵션을 설명합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PresentationConvertOptions()](#PresentationConvertOptions--) | [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions) 클래스를 새 인스턴스로 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPassword()](#getPassword--) | 변환된 문서를 비밀번호로 보호하려면 이 속성을 설정하십시오. |
| [setPassword(String value)](#setPassword-java.lang.String-) | 변환된 문서를 비밀번호로 보호하려면 이 속성을 설정하십시오. |
| [getZoom()](#getZoom--) | 줌 레벨을 백분율로 지정합니다. |
| [setZoom(int value)](#setZoom-int-) | 줌 레벨을 백분율로 지정합니다. |
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


[PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions) 클래스를 새 인스턴스로 초기화합니다.

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


줌 레벨을 백분율로 지정합니다. 기본값은 100입니다. 기본 줌은 Microsoft Powerpoint 2010까지 지원됩니다. Microsoft Powerpoint 2013부터는 기본 줌이 문서에 설정되지 않고, 대신 마지막으로 열린 문서의 줌 계수를 사용하는 것으로 보입니다.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


줌 레벨을 백분율로 지정합니다. 기본값은 100입니다. 기본 줌은 Microsoft Powerpoint 2010까지 지원됩니다. Microsoft Powerpoint 2013부터는 기본 줌이 문서에 설정되지 않고, 대신 마지막으로 열린 문서의 줌 계수를 사용하는 것으로 보입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

