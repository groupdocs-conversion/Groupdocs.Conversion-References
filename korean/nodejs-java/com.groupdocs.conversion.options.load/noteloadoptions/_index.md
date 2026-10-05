---
title: "NoteLoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "One 문서를 로드하기 위한 옵션."
type: docs
weight: 27
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/noteloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class NoteLoadOptions extends LoadOptions implements Serializable
```

One 문서를 로드하기 위한 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [NoteLoadOptions()](#NoteLoadOptions--) | 새 인스턴스를 초기화합니다 [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Note 문서의 기본 글꼴. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Note 문서의 기본 글꼴. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Note 문서를 변환할 때 특정 글꼴을 대체합니다. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Note 문서를 변환할 때 특정 글꼴을 대체합니다. |
| [getPassword()](#getPassword--) | 보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다. |
| [setPassword(String value)](#setPassword-java.lang.String-) | 보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다. |
### NoteLoadOptions() {#NoteLoadOptions--}
```
public NoteLoadOptions()
```


새 인스턴스를 초기화합니다 [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions) 클래스.

### getFormat() {#getFormat--}
```
public final NoteFileType getFormat()
```


입력 문서 파일 유형

**Returns:**
[NoteFileType](../../com.groupdocs.conversion.filetypes/notefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Note 문서의 기본 글꼴. 글꼴이 없을 경우 다음 글꼴이 사용됩니다.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Note 문서의 기본 글꼴. 글꼴이 없을 경우 다음 글꼴이 사용됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Note 문서를 변환할 때 특정 글꼴을 대체합니다.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Note 문서를 변환할 때 특정 글꼴을 대체합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

