---
title: "ConversionNotSupportedException"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Eccezione GroupDocs sollevata quando la conversione dal file sorgente al tipo di file di destinazione non è supportata"
type: docs
weight: 10
url: /it/java/com.groupdocs.conversion.exceptions/conversionnotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class ConversionNotSupportedException extends GroupDocsConversionException
```

Eccezione GroupDocs sollevata quando la conversione dal file sorgente al tipo di file di destinazione non è supportata

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ConversionNotSupportedException()](#ConversionNotSupportedException--) | Costruttore predefinito |
|
|  | [ConversionNotSupportedException(FileType source, FileType target)](#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Crea un'istanza di eccezione con un FileType di origine e un Filetype di destinazione |
|
|  | [ConversionNotSupportedException(String message)](#ConversionNotSupportedException-java.lang.String-) | Crea un'istanza di eccezione con un messaggio |
|
### ConversionNotSupportedException() {#ConversionNotSupportedException--}
```
public ConversionNotSupportedException()
```


Costruttore predefinito


### ConversionNotSupportedException(FileType source, FileType target) {#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionNotSupportedException(FileType source, FileType target)
```


Crea un'istanza di eccezione con un FileType di origine e un Filetype di destinazione


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Il tipo di file di origine |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Il tipo di file di destinazione |
|

### ConversionNotSupportedException(String message) {#ConversionNotSupportedException-java.lang.String-}
```
public ConversionNotSupportedException(String message)
```


Crea un'istanza di eccezione con un messaggio


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | messaggio | java.lang.String | Il messaggio |
|

