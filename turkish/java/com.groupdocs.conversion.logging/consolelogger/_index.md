---
title: "ConsoleLogger"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Konsol günlükleyici uygulaması."
type: docs
weight: 10
url: /tr/java/com.groupdocs.conversion.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

Konsol günlükleyici uygulaması.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [trace(String message)](#trace-java.lang.String-) | İzleme günlük mesajı yazar; |
İzleme günlük mesajları, uygulama akışı hakkında genellikle yararlı bilgiler sağlar.
|
|  | [warning(String message)](#warning-java.lang.String-) | Uyarı günlük mesajı yazar; |
Uyarı günlük mesajları, uygulama akışındaki beklenmeyen ve kurtarılabilir olaylar hakkında bilgi sağlar.
|
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Hata günlük mesajı yazar; |
Hata günlük mesajları, uygulama akışındaki kurtarılamaz olaylar hakkında bilgi sağlar.
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


İzleme günlük mesajı yazar;
İzleme günlük mesajları, uygulama akışı hakkında genellikle yararlı bilgiler sağlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | İzleme mesajı. |
|

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


Uyarı günlük mesajı yazar;
Uyarı günlük mesajları, uygulama akışındaki beklenmeyen ve kurtarılabilir olaylar hakkında bilgi sağlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Uyarı mesajı. |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


Hata günlük mesajı yazar;
Hata günlük mesajları, uygulama akışındaki kurtarılamaz olaylar hakkında bilgi sağlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Hata mesajı. |
|
|  | istisna | java.lang.Exception | İstisna. |
|

