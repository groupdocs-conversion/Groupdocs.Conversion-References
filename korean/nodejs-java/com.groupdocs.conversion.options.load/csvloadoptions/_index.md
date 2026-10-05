---
title: "CsvLoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Csv 문서 불러오기 옵션."
type: docs
weight: 14
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

Csv 문서 불러오기 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CsvLoadOptions()](#CsvLoadOptions--) | 새로운 [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSeparator()](#getSeparator--) | Csv 파일의 구분자. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Csv 파일의 구분자. |
| [setSeparator(char value)](#setSeparator-char-) | Csv 파일의 구분자. |
| [isMultiEncoded()](#isMultiEncoded--) | True는 파일에 여러 인코딩이 포함되어 있음을 의미합니다. |
| [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | True는 파일에 여러 인코딩이 포함되어 있음을 의미합니다. |
| [hasFormula()](#hasFormula--) | 텍스트가 "="로 시작하면 수식인지 여부를 나타냅니다. |
| [setFormula(boolean value)](#setFormula-boolean-) | 텍스트가 "="로 시작하면 수식인지 여부를 나타냅니다. |
| [getConvertNumericData()](#getConvertNumericData--) | 파일 내 문자열이 숫자로 변환되는지 여부를 나타냅니다. |
| [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | 파일 내 문자열이 숫자로 변환되는지 여부를 나타냅니다. |
| [getConvertDateTimeData()](#getConvertDateTimeData--) | 파일의 문자열이 날짜로 변환되는지 여부를 나타냅니다. |
| [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | 파일의 문자열이 날짜로 변환되는지 여부를 나타냅니다. |
| [getEncoding()](#getEncoding--) | 인코딩. |
| [getEncodingInternal()](#getEncodingInternal--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 인코딩. |
| [setEncoding(String charsetName)](#setEncoding-java.lang.String-) | Txt 문서를 로드할 때 사용할 인코딩을 가져오거나 설정합니다. |
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


새로운 [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions) 클래스 인스턴스를 초기화합니다.

### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Csv 파일의 구분자.

**Returns:**
char
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Csv 파일의 구분자.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

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
boolean
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


True는 파일에 여러 인코딩이 포함되어 있음을 의미합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


텍스트가 "="로 시작하면 수식인지 여부를 나타냅니다.

**Returns:**
boolean
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


텍스트가 "="로 시작하면 수식인지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


파일의 문자열이 숫자로 변환되는지 여부를 나타냅니다. 기본값은 True입니다.

**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


파일의 문자열이 숫자로 변환되는지 여부를 나타냅니다. 기본값은 True입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


파일의 문자열이 날짜로 변환되는지 여부를 나타냅니다. 기본값은 True입니다.

**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


파일의 문자열이 날짜로 변환되는지 여부를 나타냅니다. 기본값은 True입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


인코딩. 기본값은 Encoding.Default입니다.

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


인코딩. 기본값은 Encoding.Default입니다.

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

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.ms.System.Text.Encoding |  |

