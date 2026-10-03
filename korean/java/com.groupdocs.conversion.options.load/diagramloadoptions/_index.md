---
title: "DiagramLoadOptions"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "다이어그램 문서를 로드하기 위한 옵션."
type: docs
weight: 15
url: /ko/java/com.groupdocs.conversion.options.load/diagramloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramLoadOptions extends LoadOptions implements Serializable
```

다이어그램 문서를 로드하기 위한 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DiagramLoadOptions()](#DiagramLoadOptions--) | [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions) 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Diagram 문서의 기본 글꼴. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Diagram 문서의 기본 글꼴. |
|
### DiagramLoadOptions() {#DiagramLoadOptions--}
```
public DiagramLoadOptions()
```


[DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions) 클래스의 새 인스턴스를 초기화합니다.


### getFormat() {#getFormat--}
```
public final DiagramFileType getFormat()
```


입력 문서 파일 유형


**Returns:**
[DiagramFileType](../../com.groupdocs.conversion.filetypes/diagramfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Diagram 문서의 기본 글꼴입니다. 글꼴이 없을 경우 다음 글꼴이 사용됩니다.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Diagram 문서의 기본 글꼴입니다. 글꼴이 없을 경우 다음 글꼴이 사용됩니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

