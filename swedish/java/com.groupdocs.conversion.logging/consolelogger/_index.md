---
title: "ConsoleLogger"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Implementering av konsolloggare."
type: docs
weight: 10
url: /sv/java/com.groupdocs.conversion.logging/consolelogger/
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
|  | [trace(String message)](#trace-java.lang.String-) | Skriver spårloggmeddelande; |
Spårloggmeddelanden ger allmänt användbar information om applikationsflödet.
|
|  | [warning(String message)](#warning-java.lang.String-) | Skriver varningsloggmeddelande; |
Varningsloggmeddelanden ger information om oväntade och återhämtningsbara händelser i applikationsflödet.
|
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Skriver fel loggmeddelande; |
Felloggmeddelanden ger information om oåterhämtningsbara händelser i applikationsflödet.
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


Skriver spårloggmeddelande;
Spårloggmeddelanden ger allmänt användbar information om applikationsflödet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Spårmeddelandet. |
|

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


Skriver varningsloggmeddelande;
Varningsloggmeddelanden ger information om oväntade och återhämtningsbara händelser i applikationsflödet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Varningsmeddelandet. |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


Skriver fel loggmeddelande;
Felloggmeddelanden ger information om oåterhämtningsbara händelser i applikationsflödet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Felmeddelandet. |
|
|  | undantag | java.lang.Exception | Undantaget. |
|

