---
title: "ConsoleLogger"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Console logger-implementatie."
type: docs
weight: 10
url: /nl/nodejs-java/com.groupdocs.conversion.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

Console logger-implementatie.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | Schrijft traceerlogbericht; Traceerlogberichten bieden over het algemeen nuttige informatie over de applicatiestroom. |
| [warning(String message)](#warning-java.lang.String-) | Schrijft waarschuwingslogbericht; Waarschuwingslogberichten bieden informatie over onverwachte en herstelbare gebeurtenissen in de applicatiestroom. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Schrijft foutlogbericht; Foutlogberichten bieden informatie over onherstelbare gebeurtenissen in de applicatiestroom. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


Schrijft traceerlogbericht; Traceerlogberichten bieden over het algemeen nuttige informatie over de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het traceerbericht. |

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


Schrijft waarschuwingslogbericht; Waarschuwingslogberichten bieden informatie over onverwachte en herstelbare gebeurtenissen in de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het waarschuwingsbericht. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


Schrijft foutlogbericht; Foutlogberichten bieden informatie over onherstelbare gebeurtenissen in de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het foutbericht. |
| exceptie | java.lang.Exception | De exceptie. |

