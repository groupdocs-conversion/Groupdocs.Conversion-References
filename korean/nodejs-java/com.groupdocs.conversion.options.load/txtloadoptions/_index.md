---
title: "TxtLoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Txt 문서를 로드하기 위한 옵션."
type: docs
weight: 38
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

Txt 문서를 로드하기 위한 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TxtLoadOptions()](#TxtLoadOptions--) | 새 인스턴스를 초기화합니다 [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | 일반 텍스트 문서를 변환할 때 번호 매기기 목록 항목이 인식되는 방식을 지정할 수 있습니다. |
| [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | 일반 텍스트 문서를 변환할 때 번호 매기기 목록 항목이 인식되는 방식을 지정할 수 있습니다. |
| [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | 후행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. |
| [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | 후행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. |
| [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | 선행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. |
| [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | 선행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. |
| [getEncoding()](#getEncoding--) | Txt 문서를 로드할 때 사용할 인코딩을 가져오거나 설정합니다. |
| [getEncodingInternal()](#getEncodingInternal--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Txt 문서를 로드할 때 사용할 인코딩을 가져오거나 설정합니다. |
| [setEncoding(String charsetName)](#setEncoding-java.lang.String-) | Txt 문서를 로드할 때 사용할 인코딩을 가져오거나 설정합니다. |
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


새 인스턴스를 초기화합니다 [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions) 클래스.

### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


입력 문서 파일 유형

**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


일반 텍스트 문서를 변환할 때 번호 매기기 목록 항목이 인식되는 방식을 지정할 수 있습니다. 기본값은 true입니다.

--------------------

이 옵션을 false로 설정하면, 목록 인식 알고리즘은 목록 번호가 마침표, 오른쪽 대괄호 또는 글머리 기호(예: "\\u2022", "*", "-" 또는 "o")로 끝날 때 목록 단락을 감지합니다.

이 옵션을 true로 설정하면, 공백도 목록 번호 구분 기호로 사용됩니다: 아라비아식 번호 매기기(1., 1.1.2.)에 대한 목록 인식 알고리즘은 공백과 마침표(".") 기호를 모두 사용합니다.

**Returns:**
boolean
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


일반 텍스트 문서를 변환할 때 번호 매기기 목록 항목이 인식되는 방식을 지정할 수 있습니다. 기본값은 true입니다.

--------------------

이 옵션을 false로 설정하면, 목록 인식 알고리즘은 목록 번호가 마침표, 오른쪽 대괄호 또는 글머리 기호(예: "\\u2022", "*", "-" 또는 "o")로 끝날 때 목록 단락을 감지합니다.

이 옵션을 true로 설정하면, 공백도 목록 번호 구분 기호로 사용됩니다: 아라비아식 번호 매기기(1., 1.1.2.)에 대한 목록 인식 알고리즘은 공백과 마침표(".") 기호를 모두 사용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


후행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. 기본값은 [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions\#Trim)입니다.

**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


후행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. 기본값은 [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions\#Trim)입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


선행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. 기본값은 [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions\#ConvertToIndent)입니다.

**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


선행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. 기본값은 [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions\#ConvertToIndent)입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Txt 문서를 로드할 때 사용할 인코딩을 가져오거나 설정합니다. null일 수 있습니다. 기본값은 null입니다.

**Returns:**
java.nio.charset.Charset
### getEncodingInternal() {#getEncodingInternal--}
```
public System.Text.Encoding getEncodingInternal()
```




**Returns:**
com.aspose.ms.System.Text.Encoding
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Txt 문서를 로드할 때 사용할 인코딩을 가져오거나 설정합니다. null일 수 있습니다. 기본값은 null입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.nio.charset.Charset |  |

### setEncoding(String charsetName) {#setEncoding-java.lang.String-}
```
public final void setEncoding(String charsetName)
```


Txt 문서를 로드할 때 사용할 인코딩을 가져오거나 설정합니다. null일 수 있습니다. 기본값은 null입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| charsetName | java.lang.String |  |

