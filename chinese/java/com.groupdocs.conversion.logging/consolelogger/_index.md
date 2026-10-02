---
title: "ConsoleLogger"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "控制台日志实现。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.conversion.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

控制台日志实现。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [trace(String message)](#trace-java.lang.String-) | 写入跟踪日志消息; |
跟踪日志消息提供有关应用程序流程的一般有用信息。
|
|  | [warning(String message)](#warning-java.lang.String-) | 写入警告日志消息; |
警告日志消息提供有关应用程序流程中意外且可恢复事件的信息。
|
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | 写入错误日志消息; |
错误日志消息提供有关应用程序流程中不可恢复事件的信息。
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


写入跟踪日志消息;
跟踪日志消息提供有关应用程序流程的一般有用信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消息 | java.lang.String | 跟踪消息。 |
|

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


写入警告日志消息;
警告日志消息提供有关应用程序流程中意外且可恢复事件的信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消息 | java.lang.String | 警告消息。 |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


写入错误日志消息;
错误日志消息提供有关应用程序流程中不可恢复事件的信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消息 | java.lang.String | 错误消息。 |
|
|  | 异常 | java.lang.Exception | 异常。 |
|

