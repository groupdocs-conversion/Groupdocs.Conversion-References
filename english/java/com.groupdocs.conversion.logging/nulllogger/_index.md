---
title: NullLogger
second_title: GroupDocs.Conversion for Java API Reference
description: Null logger implementation.
type: docs
weight: 11
url: /java/com.groupdocs.conversion.logging/nulllogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class NullLogger implements ILogger
```

Null logger implementation. Means that logging is not used
## Fields

| Field | Description |
| --- | --- |
| [Instance](#Instance) |  |
## Methods

| Method | Description |
| --- | --- |
| [error(String message, System.Exception exception)](#error-java.lang.String-com.aspose.ms.System.Exception-) |  |
| [warning(String message)](#warning-java.lang.String-) |  |
| [trace(String message)](#trace-java.lang.String-) |  |
### Instance {#Instance}
```
public static final NullLogger Instance
```


### error(String message, System.Exception exception) {#error-java.lang.String-com.aspose.ms.System.Exception-}
```
public final void error(String message, System.Exception exception)
```


Writes error log message; Error log messages provides information about unrecoverable events in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String |  |
| exception | com.aspose.ms.System.Exception |  |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Writes warning log message; Warning log messages provides information about unexpected and recoverable event in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String |  |

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Writes trace log message; Trace log messages provides generally useful information about application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String |  |

