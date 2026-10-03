---
title: "ConsoleLogger"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Υλοποίηση καταγραφέα κονσόλας."
type: docs
weight: 10
url: /el/java/com.groupdocs.conversion.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

Υλοποίηση καταγραφέα κονσόλας.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [trace(String message)](#trace-java.lang.String-) | Γράφει μήνυμα καταγραφής εντοπισμού; |
Τα μηνύματα καταγραφής εντοπισμού παρέχουν γενικά χρήσιμες πληροφορίες σχετικά με τη ροή της εφαρμογής.
|
|  | [warning(String message)](#warning-java.lang.String-) | Γράφει μήνυμα προειδοποίησης καταγραφής; |
Τα μηνύματα προειδοποίησης καταγραφής παρέχουν πληροφορίες σχετικά με απρόσμενα και ανακτήσιμα γεγονότα στη ροή της εφαρμογής.
|
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Γράφει μήνυμα σφάλματος καταγραφής; |
Τα μηνύματα σφάλματος καταγραφής παρέχουν πληροφορίες σχετικά με μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


Γράφει μήνυμα καταγραφής εντοπισμού;
Τα μηνύματα καταγραφής εντοπισμού παρέχουν γενικά χρήσιμες πληροφορίες σχετικά με τη ροή της εφαρμογής.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Το μήνυμα εντοπισμού. |
|

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


Γράφει μήνυμα προειδοποίησης καταγραφής;
Τα μηνύματα προειδοποίησης καταγραφής παρέχουν πληροφορίες σχετικά με απρόσμενα και ανακτήσιμα γεγονότα στη ροή της εφαρμογής.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Το μήνυμα προειδοποίησης. |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


Γράφει μήνυμα σφάλματος καταγραφής;
Τα μηνύματα σφάλματος καταγραφής παρέχουν πληροφορίες σχετικά με μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Το μήνυμα σφάλματος. |
|
|  | εξαίρεση | java.lang.Exception | Η εξαίρεση. |
|

