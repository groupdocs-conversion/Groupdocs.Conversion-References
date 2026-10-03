---
title: "ConversionNotSupportedException"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "GroupDocs-Ausnahme, die ausgelöst wird, wenn die Konvertierung von Quelldatei zu Ziel-Dateityp nicht unterstützt wird."
type: docs
weight: 10
url: /de/java/com.groupdocs.conversion.exceptions/conversionnotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class ConversionNotSupportedException extends GroupDocsConversionException
```

GroupDocs-Ausnahme, die ausgelöst wird, wenn die Konvertierung von Quelldatei zu Ziel-Dateityp nicht unterstützt wird.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ConversionNotSupportedException()](#ConversionNotSupportedException--) | Standardkonstruktor |
|
|  | [ConversionNotSupportedException(FileType source, FileType target)](#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Erstellt eine Ausnahmeinstanz mit einem Quell-FileType und einem Ziel-Filetype |
|
|  | [ConversionNotSupportedException(String message)](#ConversionNotSupportedException-java.lang.String-) | Erstellt eine Ausnahmeinstanz mit einer Nachricht |
|
### ConversionNotSupportedException() {#ConversionNotSupportedException--}
```
public ConversionNotSupportedException()
```


Standardkonstruktor


### ConversionNotSupportedException(FileType source, FileType target) {#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionNotSupportedException(FileType source, FileType target)
```


Erstellt eine Ausnahmeinstanz mit einem Quell-FileType und einem Ziel-Filetype


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Der Quell-Dateityp |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Der Ziel-Dateityp |
|

### ConversionNotSupportedException(String message) {#ConversionNotSupportedException-java.lang.String-}
```
public ConversionNotSupportedException(String message)
```


Erstellt eine Ausnahmeinstanz mit einer Nachricht


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Nachricht | java.lang.String | Die Nachricht |
|

