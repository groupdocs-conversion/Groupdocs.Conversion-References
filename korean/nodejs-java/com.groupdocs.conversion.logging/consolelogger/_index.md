---
title: "콘솔 로거"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "콘솔 로거 구현."
type: docs
weight: 10
url: /ko/nodejs-java/com.groupdocs.conversion.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

콘솔 로거 구현.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | 추적 로그 메시지를 기록합니다; 추적 로그 메시지는 애플리케이션 흐름에 대한 일반적으로 유용한 정보를 제공합니다. |
| [warning(String message)](#warning-java.lang.String-) | 경고 로그 메시지를 기록합니다; 경고 로그 메시지는 애플리케이션 흐름에서 예상치 못한 복구 가능한 이벤트에 대한 정보를 제공합니다. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | 오류 로그 메시지를 기록합니다; 오류 로그 메시지는 애플리케이션 흐름에서 복구 불가능한 이벤트에 대한 정보를 제공합니다. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


추적 로그 메시지를 기록합니다; 추적 로그 메시지는 애플리케이션 흐름에 대한 일반적으로 유용한 정보를 제공합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메시지 | java.lang.String | 추적 메시지. |

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


경고 로그 메시지를 기록합니다; 경고 로그 메시지는 애플리케이션 흐름에서 예상치 못한 복구 가능한 이벤트에 대한 정보를 제공합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메시지 | java.lang.String | 경고 메시지. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


오류 로그 메시지를 기록합니다; 오류 로그 메시지는 애플리케이션 흐름에서 복구 불가능한 이벤트에 대한 정보를 제공합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메시지 | java.lang.String | 오류 메시지. |
| 예외 | java.lang.Exception | 예외입니다. |

