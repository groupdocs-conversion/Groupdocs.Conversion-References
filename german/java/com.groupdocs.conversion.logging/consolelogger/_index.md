---
title: "ConsoleLogger"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Implementierung des Konsolen-Loggers."
type: docs
weight: 10
url: /de/java/com.groupdocs.conversion.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

Implementierung des Konsolen-Loggers.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [trace(String message)](#trace-java.lang.String-) | Schreibt Trace-Protokollnachricht; |
Trace-Protokollnachrichten liefern allgemein nützliche Informationen über den Anwendungsablauf.
|
|  | [warning(String message)](#warning-java.lang.String-) | Schreibt Warnungsprotokollnachricht; |
Warnungsprotokollnachrichten liefern Informationen über unerwartete und wiederherstellbare Ereignisse im Anwendungsablauf.
|
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Schreibt Fehlermeldungsprotokoll; |
Fehlerprotokollnachrichten liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


Schreibt Trace-Protokollnachricht;
Trace-Protokollnachrichten liefern allgemein nützliche Informationen über den Anwendungsablauf.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Nachricht | java.lang.String | Die Trace-Nachricht. |
|

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


Schreibt Warnungsprotokollnachricht;
Warnungsprotokollnachrichten liefern Informationen über unerwartete und wiederherstellbare Ereignisse im Anwendungsablauf.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Nachricht | java.lang.String | Die Warnmeldung. |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


Schreibt Fehlermeldungsprotokoll;
Fehlerprotokollnachrichten liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Nachricht | java.lang.String | Die Fehlermeldung. |
|
|  | Ausnahme | java.lang.Exception | Die Ausnahme. |
|

