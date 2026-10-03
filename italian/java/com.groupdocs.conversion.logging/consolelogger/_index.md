---
title: "ConsoleLogger"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Implementazione del logger console."
type: docs
weight: 10
url: /it/java/com.groupdocs.conversion.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

Implementazione del logger console.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [trace(String message)](#trace-java.lang.String-) | Scrive messaggio di log di traccia; |
I messaggi di log di traccia forniscono informazioni generalmente utili sul flusso dell'applicazione.
|
|  | [warning(String message)](#warning-java.lang.String-) | Scrive messaggio di log di avviso; |
I messaggi di log di avviso forniscono informazioni su eventi inaspettati e recuperabili nel flusso dell'applicazione.
|
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Scrive messaggio di log di errore; |
I messaggi di log di errore forniscono informazioni su eventi non recuperabili nel flusso dell'applicazione.
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


Scrive messaggio di log di traccia;
I messaggi di log di traccia forniscono informazioni generalmente utili sul flusso dell'applicazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | messaggio | java.lang.String | Il messaggio di traccia. |
|

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


Scrive messaggio di log di avviso;
I messaggi di log di avviso forniscono informazioni su eventi inaspettati e recuperabili nel flusso dell'applicazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | messaggio | java.lang.String | Il messaggio di avviso. |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


Scrive messaggio di log di errore;
I messaggi di log di errore forniscono informazioni su eventi non recuperabili nel flusso dell'applicazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | messaggio | java.lang.String | Il messaggio di errore. |
|
|  | eccezione | java.lang.Exception | L'eccezione. |
|

