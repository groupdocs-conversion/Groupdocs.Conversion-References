---
title: "ConsoleLogger"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "تنفيذ مسجل وحدة التحكم."
type: docs
weight: 10
url: /ar/java/com.groupdocs.conversion.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

تنفيذ مسجل وحدة التحكم.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [trace(String message)](#trace-java.lang.String-) | يكتب رسالة سجل التتبع؛ |
توفر رسائل سجل التتبع معلومات عامة مفيدة حول تدفق التطبيق.
|
|  | [warning(String message)](#warning-java.lang.String-) | يكتب رسالة سجل التحذير؛ |
توفر رسائل سجل التحذير معلومات حول حدث غير متوقع وقابل للاسترداد في تدفق التطبيق.
|
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | يكتب رسالة سجل الخطأ؛ |
توفر رسائل سجل الخطأ معلومات حول أحداث غير قابلة للاسترداد في تدفق التطبيق.
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


يكتب رسالة سجل التتبع؛
توفر رسائل سجل التتبع معلومات عامة مفيدة حول تدفق التطبيق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | رسالة | java.lang.String | رسالة التتبع. |
|

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


يكتب رسالة سجل التحذير؛
توفر رسائل سجل التحذير معلومات حول حدث غير متوقع وقابل للاسترداد في تدفق التطبيق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | رسالة | java.lang.String | رسالة التحذير. |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


يكتب رسالة سجل الخطأ؛
توفر رسائل سجل الخطأ معلومات حول أحداث غير قابلة للاسترداد في تدفق التطبيق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | رسالة | java.lang.String | رسالة الخطأ. |
|
|  | استثناء | java.lang.Exception | الاستثناء. |
|

