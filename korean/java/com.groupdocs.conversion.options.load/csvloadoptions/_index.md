---
title: "CsvLoadOptions"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "Csv 문서 로드 옵션."
type: docs
weight: 13
url: /ko/java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

Csv 문서 로드 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [CsvLoadOptions()](#CsvLoadOptions--) | 새 인스턴스를 초기화합니다. [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions) 클래스. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Csv 파일의 구분자. |
|
|  | [setSeparator(char value)](#setSeparator-char-) | Csv 파일의 구분자. |
|
|  | [isMultiEncoded()](#isMultiEncoded--) | True는 파일에 여러 인코딩이 포함되어 있음을 의미합니다. |
|
|  | [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | True는 파일에 여러 인코딩이 포함되어 있음을 의미합니다. |
|
|  | [hasFormula()](#hasFormula--) | 텍스트가 "="로 시작하면 수식인지 여부를 나타냅니다. |
|
|  | [setFormula(boolean value)](#setFormula-boolean-) | 텍스트가 "="로 시작하면 수식인지 여부를 나타냅니다. |
|
|  | [getConvertNumericData()](#getConvertNumericData--) | 파일의 문자열이 숫자로 변환되는지 여부를 나타냅니다. |
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | 파일의 문자열이 숫자로 변환되는지 여부를 나타냅니다. |
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | 파일의 문자열이 날짜로 변환되는지 여부를 나타냅니다. |
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | 파일의 문자열이 날짜로 변환되는지 여부를 나타냅니다. |
|
|  | [getEncoding()](#getEncoding--) | 인코딩. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 인코딩. |
|
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


새 인스턴스를 초기화합니다. [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions) 클래스.


### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Csv 파일의 구분자.


**Returns:**
char
### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


Csv 파일의 구분자.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | char |  |

### isMultiEncoded() {#isMultiEncoded--}
```
public final boolean isMultiEncoded()
```


True는 파일에 여러 인코딩이 포함되어 있음을 의미합니다.


**Returns:**
불리언
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


True는 파일에 여러 인코딩이 포함되어 있음을 의미합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | 불리언 |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


텍스트가 "="로 시작하면 수식인지 여부를 나타냅니다.


**Returns:**
불리언
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


텍스트가 "="로 시작하면 수식인지 여부를 나타냅니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | 불리언 |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


파일의 문자열이 숫자로 변환되는지 여부를 나타냅니다. 기본값은 True.


**Returns:**
불리언
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


파일의 문자열이 숫자로 변환되는지 여부를 나타냅니다. 기본값은 True.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | 불리언 |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


파일의 문자열이 날짜로 변환되는지 여부를 나타냅니다. 기본값은 True.


**Returns:**
불리언
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


파일의 문자열이 날짜로 변환되는지 여부를 나타냅니다. 기본값은 True.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | 불리언 |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


인코딩. 기본값은 Encoding.Default.


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


인코딩. 기본값은 Encoding.Default.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.nio.charset.Charset |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.ms.System.Text.Encoding |  |

