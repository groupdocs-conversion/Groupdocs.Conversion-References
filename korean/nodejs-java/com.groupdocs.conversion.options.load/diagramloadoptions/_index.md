---
title: "DiagramLoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Diagram 문서 불러오기 옵션."
type: docs
weight: 16
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/diagramloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramLoadOptions extends LoadOptions implements Serializable
```

Diagram 문서 불러오기 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DiagramLoadOptions()](#DiagramLoadOptions--) | 새 인스턴스를 초기화합니다. [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Diagram 문서의 기본 폰트. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Diagram 문서의 기본 폰트. |
### DiagramLoadOptions() {#DiagramLoadOptions--}
```
public DiagramLoadOptions()
```


새 인스턴스를 초기화합니다. [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions) 클래스.

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


다이어그램 문서의 기본 글꼴입니다. 글꼴이 없을 경우 다음 글꼴이 사용됩니다.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


다이어그램 문서의 기본 글꼴입니다. 글꼴이 없을 경우 다음 글꼴이 사용됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

