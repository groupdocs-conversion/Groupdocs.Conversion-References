---
title: "ConsoleLogger"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Implementering av konsolloggare."
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.conversion.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

Implementering av konsolloggare.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | Skriver spårningsloggmeddelande; Spårningsloggmeddelanden ger allmänt användbar information om applikationsflödet. |
| [warning(String message)](#warning-java.lang.String-) | Skriver varningsloggmeddelande; Varningsloggmeddelanden ger information om oväntade och återhämtningsbara händelser i applikationsflödet. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Skriver fel-loggmeddelande; Fel-loggmeddelanden ger information om oåterhämtningsbara händelser i applikationsflödet. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


Skriver spårningsloggmeddelande; Spårningsloggmeddelanden ger allmänt användbar information om applikationsflödet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Spårningsmeddelandet. |

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


Skriver varningsloggmeddelande; Varningsloggmeddelanden ger information om oväntade och återhämtningsbara händelser i applikationsflödet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Varningsmeddelandet. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


Skriver fel-loggmeddelande; Fel-loggmeddelanden ger information om oåterhämtningsbara händelser i applikationsflödet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Felmeddelandet. |
| undantag | java.lang.Exception | Undantaget. |

