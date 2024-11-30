---
title: ConsoleLogger
second_title: GroupDocs.Conversion for Java API Reference
description: Console logger implementation.
type: docs
weight: 10
url: /java/com.groupdocs.conversion.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

Console logger implementation.
## Constructors

| Constructor | Description |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Methods

| Method | Description |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | Writes trace log message; Trace log messages provides generally useful information about application flow. |
| [warning(String message)](#warning-java.lang.String-) | Writes warning log message; Warning log messages provides information about unexpected and recoverable event in application flow. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Writes error log message; Error log messages provides information about unrecoverable events in application flow. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


Writes trace log message; Trace log messages provides generally useful information about application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The trace message. |

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


Writes warning log message; Warning log messages provides information about unexpected and recoverable event in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The warning message. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


Writes error log message; Error log messages provides information about unrecoverable events in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The error message. |
| exception | java.lang.Exception | The exception. |

