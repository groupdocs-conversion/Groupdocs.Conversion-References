---
title: "ConsoleLogger"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Реализация консольного логгера."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.conversion.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

Реализация консольного логгера.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | Записывает сообщение трассировки; сообщения трассировки предоставляют в целом полезную информацию о ходе работы приложения. |
| [warning(String message)](#warning-java.lang.String-) | Записывает сообщение предупреждения; сообщения предупреждения предоставляют информацию о неожиданных и восстанавливаемых событиях в ходе работы приложения. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Записывает сообщение об ошибке; сообщения об ошибке предоставляют информацию о необратимых событиях в ходе работы приложения. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


Записывает сообщение трассировки; сообщения трассировки предоставляют в целом полезную информацию о ходе работы приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение трассировки. |

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


Записывает сообщение предупреждения; сообщения предупреждения предоставляют информацию о неожиданных и восстанавливаемых событиях в ходе работы приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение предупреждения. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


Записывает сообщение об ошибке; сообщения об ошибке предоставляют информацию о необратимых событиях в ходе работы приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение об ошибке. |
| исключение | java.lang.Exception | Исключение. |

