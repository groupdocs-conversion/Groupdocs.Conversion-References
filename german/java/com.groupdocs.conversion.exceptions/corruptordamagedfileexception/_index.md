---
title: "CorruptOrDamagedFileException"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "GroupDocs-Ausnahme, die ausgelöst wird, wenn die Datei beschädigt oder defekt ist."
type: docs
weight: 11
url: /de/java/com.groupdocs.conversion.exceptions/corruptordamagedfileexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class CorruptOrDamagedFileException extends GroupDocsConversionException
```

GroupDocs-Ausnahme, die ausgelöst wird, wenn die Datei beschädigt oder defekt ist.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [CorruptOrDamagedFileException()](#CorruptOrDamagedFileException--) | Standardkonstruktor |
|
|  | [CorruptOrDamagedFileException(FileType fileType)](#CorruptOrDamagedFileException-com.groupdocs.conversion.filetypes.FileType-) | Erstellt eine Ausnahmeinstanz mit einem FileType |
|
|  | [CorruptOrDamagedFileException(String message)](#CorruptOrDamagedFileException-java.lang.String-) | Erstellt eine Ausnahmeinstanz mit einer Nachricht |
|
|  | [CorruptOrDamagedFileException(String message, RuntimeException exception)](#CorruptOrDamagedFileException-java.lang.String-java.lang.RuntimeException-) | Erstellt eine Ausnahmeinstanz mit einer Nachricht und propagiert die innere Ausnahme |
|
### CorruptOrDamagedFileException() {#CorruptOrDamagedFileException--}
```
public CorruptOrDamagedFileException()
```


Standardkonstruktor


### CorruptOrDamagedFileException(FileType fileType) {#CorruptOrDamagedFileException-com.groupdocs.conversion.filetypes.FileType-}
```
public CorruptOrDamagedFileException(FileType fileType)
```


Erstellt eine Ausnahmeinstanz mit einem FileType


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Der Dateityp |
|

### CorruptOrDamagedFileException(String message) {#CorruptOrDamagedFileException-java.lang.String-}
```
public CorruptOrDamagedFileException(String message)
```


Erstellt eine Ausnahmeinstanz mit einer Nachricht


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Nachricht | java.lang.String | Die Nachricht |
|

### CorruptOrDamagedFileException(String message, RuntimeException exception) {#CorruptOrDamagedFileException-java.lang.String-java.lang.RuntimeException-}
```
public CorruptOrDamagedFileException(String message, RuntimeException exception)
```


Erstellt eine Ausnahmeinstanz mit einer Nachricht und propagiert die innere Ausnahme


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Nachricht | java.lang.String | Die Nachricht |
|
|  | Ausnahme | java.lang.RuntimeException | Die innere Ausnahme |
|

