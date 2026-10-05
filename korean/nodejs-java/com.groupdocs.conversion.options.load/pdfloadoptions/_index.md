---
title: "PdfLoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Pdf 문서를 로드하기 위한 옵션."
type: docs
weight: 31
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfLoadOptions extends LoadOptions implements Serializable
```

Pdf 문서를 로드하기 위한 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) | 새로운 [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | 임베디드 파일을 제거합니다. |
| [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | 임베디드 파일을 제거합니다. |
| [getPassword()](#getPassword--) | 보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다. |
| [setPassword(String value)](#setPassword-java.lang.String-) | 보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다. |
| [getDefaultFont()](#getDefaultFont--) | Pdf 문서의 기본 글꼴. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Pdf 문서의 기본 글꼴. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Pdf 문서를 변환할 때 특정 글꼴을 대체합니다. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Pdf 문서를 변환할 때 특정 글꼴을 대체합니다. |
| [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Pdf 문서의 주석을 숨깁니다. |
| [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Pdf 문서의 주석을 숨깁니다. |
| [getFlattenAllFields()](#getFlattenAllFields--) | PDF 양식의 모든 필드를 평면화합니다. |
| [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | PDF 양식의 모든 필드를 평면화합니다. |
| [getResetFontFolders()](#getResetFontFolders--) | 문서를 로드하기 전에 폰트 폴더를 재설정합니다 |
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


새로운 [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions) 클래스 인스턴스를 초기화합니다.

### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


입력 문서 파일 유형

**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


임베디드 파일을 제거합니다.

**Returns:**
boolean
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


임베디드 파일을 제거합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Pdf 문서의 기본 글꼴. 글꼴이 없을 경우 다음 글꼴이 사용됩니다.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Pdf 문서의 기본 글꼴. 글꼴이 없을 경우 다음 글꼴이 사용됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Pdf 문서를 변환할 때 특정 글꼴을 대체합니다.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Pdf 문서를 변환할 때 특정 글꼴을 대체합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getHidePdfAnnotations() {#getHidePdfAnnotations--}
```
public final boolean getHidePdfAnnotations()
```


Pdf 문서의 주석을 숨깁니다.

**Returns:**
boolean
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


Pdf 문서의 주석을 숨깁니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


PDF 양식의 모든 필드를 평면화합니다.

**Returns:**
boolean
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


PDF 양식의 모든 필드를 평면화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


문서를 로드하기 전에 폰트 폴더를 재설정합니다

**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| resetFontFolders | boolean |  |

