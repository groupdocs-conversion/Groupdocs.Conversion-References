---
title: "ConsoleLogger"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Implementación del registrador de consola."
type: docs
weight: 10
url: /es/java/com.groupdocs.conversion.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

Implementación del registrador de consola.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [trace(String message)](#trace-java.lang.String-) | Escribe mensaje de registro de traza; |
Los mensajes de registro de traza proporcionan información generalmente útil sobre el flujo de la aplicación.
|
|  | [warning(String message)](#warning-java.lang.String-) | Escribe mensaje de registro de advertencia; |
Los mensajes de registro de advertencia proporcionan información sobre eventos inesperados y recuperables en el flujo de la aplicación.
|
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Escribe mensaje de registro de error; |
Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación.
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


Escribe mensaje de registro de traza;
Los mensajes de registro de traza proporcionan información generalmente útil sobre el flujo de la aplicación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | mensaje | java.lang.String | El mensaje de traza. |
|

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


Escribe mensaje de registro de advertencia;
Los mensajes de registro de advertencia proporcionan información sobre eventos inesperados y recuperables en el flujo de la aplicación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | mensaje | java.lang.String | El mensaje de advertencia. |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


Escribe mensaje de registro de error;
Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | mensaje | java.lang.String | El mensaje de error. |
|
|  | excepción | java.lang.Exception | La excepción. |
|

