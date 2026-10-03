---
title: "ConsoleLogger"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Implementasi logger konsol."
type: docs
weight: 10
url: /id/java/com.groupdocs.conversion.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

Implementasi logger konsol.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [trace(String message)](#trace-java.lang.String-) | Menulis pesan log jejak; |
Pesan log jejak menyediakan informasi yang umumnya berguna tentang alur aplikasi.
|
|  | [warning(String message)](#warning-java.lang.String-) | Menulis pesan log peringatan; |
Pesan log peringatan menyediakan informasi tentang peristiwa tak terduga dan dapat dipulihkan dalam alur aplikasi.
|
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Menulis pesan log kesalahan; |
Pesan log kesalahan menyediakan informasi tentang peristiwa yang tidak dapat dipulihkan dalam alur aplikasi.
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


Menulis pesan log jejak;
Pesan log jejak menyediakan informasi yang umumnya berguna tentang alur aplikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pesan | java.lang.String | Pesan jejak. |
|

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


Menulis pesan log peringatan;
Pesan log peringatan menyediakan informasi tentang peristiwa tak terduga dan dapat dipulihkan dalam alur aplikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pesan | java.lang.String | Pesan peringatan. |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


Menulis pesan log kesalahan;
Pesan log kesalahan menyediakan informasi tentang peristiwa yang tidak dapat dipulihkan dalam alur aplikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pesan | java.lang.String | Pesan kesalahan. |
|
|  | eksepsi | java.lang.Exception | Pengecualian. |
|

