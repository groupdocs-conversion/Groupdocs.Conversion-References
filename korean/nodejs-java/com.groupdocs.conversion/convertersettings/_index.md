---
title: "ConverterSettings"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "동작을 사용자 지정하기 위한 설정을 정의합니다."
type: docs
weight: 11
url: /ko/nodejs-java/com.groupdocs.conversion/convertersettings/
---
**Inheritance:**
java.lang.Object
```
public final class ConverterSettings
```

동작을 사용자 지정하기 위한 설정을 정의합니다 [Converter](../../com.groupdocs.conversion/converter).
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ConverterSettings()](#ConverterSettings--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCache()](#getCache--) | 변환 결과를 저장하는 데 사용되는 캐시 구현. |
| [setCache(ICache value)](#setCache-com.groupdocs.conversion.caching.ICache-) | 변환 결과를 저장하는 데 사용되는 캐시 구현. |
| [getLogger()](#getLogger--) | 변환 프로세스를 로깅하는 데 사용되는 로거 구현. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.conversion.logging.ILogger-) | 변환 프로세스를 로깅하는 데 사용되는 로거 구현. |
| [getListener()](#getListener--) | 변환 상태 및 진행 상황을 모니터링하는 데 사용되는 converter listener 구현을 가져옵니다 |
| [setListener(IConverterListener listener)](#setListener-com.groupdocs.conversion.reporting.IConverterListener-) | 변환 상태 및 진행 상황을 모니터링하는 데 사용되는 converter listener 구현을 설정합니다 |
| [getFontDirectories()](#getFontDirectories--) | 사용자 정의 글꼴 디렉터리 경로 |
| [getFontDirectoriesInternal()](#getFontDirectoriesInternal--) |  |
| [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | 사용자 정의 글꼴 디렉터리 경로 |
| [listConverterSettings()](#listConverterSettings--) |  |
| [getTempFolder()](#getTempFolder--) | 변환에 사용되는 임시 폴더 |
| [setTempFolder(String tempFolder)](#setTempFolder-java.lang.String-) | 변환에 사용되는 임시 폴더를 설정합니다 |
### ConverterSettings() {#ConverterSettings--}
```
public ConverterSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


변환 결과를 저장하는 데 사용되는 캐시 구현.

**Returns:**
[ICache](../../com.groupdocs.conversion.caching/icache)
### setCache(ICache value) {#setCache-com.groupdocs.conversion.caching.ICache-}
```
public final void setCache(ICache value)
```


변환 결과를 저장하는 데 사용되는 캐시 구현.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.conversion.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


변환 프로세스를 로깅하는 데 사용되는 로거 구현.

**Returns:**
[ILogger](../../com.groupdocs.conversion.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.conversion.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


변환 프로세스를 로깅하는 데 사용되는 로거 구현.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.conversion.logging/ilogger) |  |

### getListener() {#getListener--}
```
public IConverterListener getListener()
```


변환 상태 및 진행 상황을 모니터링하는 데 사용되는 converter listener 구현을 가져옵니다

**Returns:**
[IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) - The converter listener
### setListener(IConverterListener listener) {#setListener-com.groupdocs.conversion.reporting.IConverterListener-}
```
public void setListener(IConverterListener listener)
```


변환 상태 및 진행 상황을 모니터링하는 데 사용되는 converter listener 구현을 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| listener | [IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) | 컨버터 리스너 |

### getFontDirectories() {#getFontDirectories--}
```
public final List<String> getFontDirectories()
```


사용자 정의 글꼴 디렉터리 경로

**Returns:**
java.util.List<java.lang.String>
### getFontDirectoriesInternal() {#getFontDirectoriesInternal--}
```
public List<String> getFontDirectoriesInternal()
```




**Returns:**
java.util.List<java.lang.String>
### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


사용자 정의 글꼴 디렉터리 경로

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.util.List<java.lang.String> |  |

### listConverterSettings() {#listConverterSettings--}
```
public List<String> listConverterSettings()
```




**Returns:**
java.util.List<java.lang.String>
### getTempFolder() {#getTempFolder--}
```
public String getTempFolder()
```


변환에 사용되는 임시 폴더

**Returns:**
java.lang.String
### setTempFolder(String tempFolder) {#setTempFolder-java.lang.String-}
```
public void setTempFolder(String tempFolder)
```


변환에 사용되는 임시 폴더를 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| tempFolder | java.lang.String |  |

