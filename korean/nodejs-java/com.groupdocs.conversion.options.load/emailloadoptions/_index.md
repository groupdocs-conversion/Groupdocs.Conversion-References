---
title: "EmailLoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Email 문서 불러오기 옵션."
type: docs
weight: 19
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Email 문서 불러오기 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [EmailLoadOptions()](#EmailLoadOptions--) | 새 인스턴스를 초기화합니다 [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDisplayHeader()](#getDisplayHeader--) | 이메일 헤더를 표시하거나 숨기는 옵션. |
| [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | 이메일 헤더를 표시하거나 숨기는 옵션. |
| [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | "from" 이메일 주소를 표시하거나 숨기는 옵션. |
| [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | "from" 이메일 주소를 표시하거나 숨기는 옵션. |
| [getDisplayEmailAddress()](#getDisplayEmailAddress--) | 이메일 주소를 표시하거나 숨기는 옵션. |
| [setDisplayEmailAddress(boolean value)](#setDisplayEmailAddress-boolean-) | 이메일 주소를 표시하거나 숨기는 옵션. |
| [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | "to" 이메일 주소를 표시하거나 숨기는 옵션. |
| [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | "to" 이메일 주소를 표시하거나 숨기는 옵션. |
| [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | "Cc" 이메일 주소를 표시하거나 숨기는 옵션. |
| [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | "Cc" 이메일 주소를 표시하거나 숨기는 옵션. |
| [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | "Bcc" 이메일 주소를 표시하거나 숨기는 옵션. |
| [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | "Bcc" 이메일 주소를 표시하거나 숨기는 옵션. |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | 메시지 날짜에 대한 협정 세계시(UTC) 오프셋을 가져오거나 설정합니다. |
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | 외부 리소스 로드 시간 초과 |
| [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | 외부 리소스 로드 시간 초과 (setter) |
| [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | 메시지 날짜에 대한 협정 세계시(UTC) 오프셋을 가져오거나 설정합니다. |
| [deepClone()](#deepClone--) | 현재 인스턴스를 복제합니다. |
| [getFieldTextMap()](#getFieldTextMap--) | 이메일 메시지와 필드 텍스트 표현 간의 매핑을 가져옵니다 |
| [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | 이메일 메시지와 필드 텍스트 표현 간의 매핑을 설정합니다 |
| [isPreserveOriginalDate()](#isPreserveOriginalDate--) | 저장 시 메일 메시지에 원본 날짜 헤더 문자열을 유지할지 여부를 정의합니다 (기본값은 true) |
| [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | 저장 시 메일 메시지에 원본 날짜 헤더 문자열을 유지할지 여부를 정의합니다 |
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### EmailLoadOptions() {#EmailLoadOptions--}
```
public EmailLoadOptions()
```


새 인스턴스를 초기화합니다 [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) 클래스.

### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


입력 문서 파일 유형

**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


이메일 헤더를 표시하거나 숨기는 옵션. 기본값: true.

**Returns:**
boolean
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


이메일 헤더를 표시하거나 숨기는 옵션. 기본값: true.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


"from" 이메일 주소를 표시하거나 숨기는 옵션. 기본값: true.

**Returns:**
boolean
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


"from" 이메일 주소를 표시하거나 숨기는 옵션. 기본값: true.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getDisplayEmailAddress() {#getDisplayEmailAddress--}
```
public final boolean getDisplayEmailAddress()
```


이메일 주소를 표시하거나 숨기는 옵션. 기본값: true.

**Returns:**
boolean
### setDisplayEmailAddress(boolean value) {#setDisplayEmailAddress-boolean-}
```
public final void setDisplayEmailAddress(boolean value)
```


이메일 주소를 표시하거나 숨기는 옵션. 기본값: true.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


"to" 이메일 주소를 표시하거나 숨기는 옵션. 기본값: true.

**Returns:**
boolean
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


"to" 이메일 주소를 표시하거나 숨기는 옵션. 기본값: true.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


"Cc" 이메일 주소를 표시하거나 숨기는 옵션입니다. 기본값: false.

**Returns:**
boolean
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


"Cc" 이메일 주소를 표시하거나 숨기는 옵션입니다. 기본값: false.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


"Bcc" 이메일 주소를 표시하거나 숨기는 옵션입니다. 기본값: false.

**Returns:**
boolean
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


"Bcc" 이메일 주소를 표시하거나 숨기는 옵션입니다. 기본값: false.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final Double getTimeZoneOffset()
```


메시지 날짜에 대한 협정 세계시(UTC) 오프셋을 가져오거나 설정합니다. 이 속성은 로컬 시간과 UTC 사이의 시간대 차이를 정의합니다.

**Returns:**
java.lang.Double
### getTimeZoneOffsetInternal() {#getTimeZoneOffsetInternal--}
```
public System.TimeSpan getTimeZoneOffsetInternal()
```




**Returns:**
com.aspose.ms.System.TimeSpan
### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public System.TimeSpan getResourceLoadingTimeout()
```


외부 리소스 로드 시간 초과

**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```


외부 리소스 로드 시간 초과 (setter)

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### setTimeZoneOffset(Double value) {#setTimeZoneOffset-java.lang.Double-}
```
public final void setTimeZoneOffset(Double value)
```


메시지 날짜에 대한 협정 세계시(UTC) 오프셋을 가져오거나 설정합니다. 이 속성은 로컬 시간과 UTC 사이의 시간대 차이를 정의합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


현재 인스턴스를 복제합니다.

**Returns:**
java.lang.Object -
### getFieldTextMap() {#getFieldTextMap--}
```
public Map<EmailField,String> getFieldTextMap()
```


이메일 메시지와 필드 텍스트 표현 간의 매핑을 가져옵니다

**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - 매핑
### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


이메일 메시지와 필드 텍스트 표현 간의 매핑을 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | 매핑 |

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


저장 시 메일 메시지에 원본 날짜 헤더 문자열을 유지할지 여부를 정의합니다 (기본값은 true)

**Returns:**
boolean - true인 경우 원본 날짜를 보존합니다
### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


저장 시 메일 메시지에 원본 날짜 헤더 문자열을 유지할지 여부를 정의합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| preserveOriginalDate | boolean | 원본 날짜 보존 |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


문서 컨테이너 자체를 변환해야 하는지 제어하는 옵션을 가져옵니다

**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


문서 컨테이너에 있는 소유 문서를 변환해야 하는지 제어하는 옵션

**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


변환을 수행할 깊이 레벨 수를 제어하는 옵션

**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 깊이 | int |  |

