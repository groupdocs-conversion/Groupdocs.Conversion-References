---
title: "ConsoleLogger"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Implémentation du journaliseur console."
type: docs
weight: 10
url: /fr/java/com.groupdocs.conversion.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

Implémentation du journaliseur console.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [trace(String message)](#trace-java.lang.String-) | Écrit le message de journal de trace; |
Les messages de journal de trace fournissent des informations généralement utiles sur le flux de l'application.
|
|  | [warning(String message)](#warning-java.lang.String-) | Écrit le message d'avertissement du journal; |
Les messages de journal d'avertissement fournissent des informations sur des événements inattendus et récupérables dans le flux de l'application.
|
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Écrit le message d'erreur du journal; |
Les messages de journal d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application.
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


Écrit le message de journal de trace;
Les messages de journal de trace fournissent des informations généralement utiles sur le flux de l'application.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message de trace. |
|

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


Écrit le message d'avertissement du journal;
Les messages de journal d'avertissement fournissent des informations sur des événements inattendus et récupérables dans le flux de l'application.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message d'avertissement. |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


Écrit le message d'erreur du journal;
Les messages de journal d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message d'erreur. |
|
|  | exception | java.lang.Exception | L'exception. |
|

