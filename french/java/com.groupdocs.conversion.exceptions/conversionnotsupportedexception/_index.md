---
title: "ConversionNotSupportedException"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Exception GroupDocs levée lorsque la conversion du fichier source vers le type de fichier cible n'est pas prise en charge"
type: docs
weight: 10
url: /fr/java/com.groupdocs.conversion.exceptions/conversionnotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class ConversionNotSupportedException extends GroupDocsConversionException
```

Exception GroupDocs levée lorsque la conversion du fichier source vers le type de fichier cible n'est pas prise en charge

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [ConversionNotSupportedException()](#ConversionNotSupportedException--) | Constructeur par défaut |
|
|  | [ConversionNotSupportedException(FileType source, FileType target)](#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Crée une instance d'exception avec un FileType source et un FileType cible |
|
|  | [ConversionNotSupportedException(String message)](#ConversionNotSupportedException-java.lang.String-) | Crée une instance d'exception avec un message |
|
### ConversionNotSupportedException() {#ConversionNotSupportedException--}
```
public ConversionNotSupportedException()
```


Constructeur par défaut


### ConversionNotSupportedException(FileType source, FileType target) {#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionNotSupportedException(FileType source, FileType target)
```


Crée une instance d'exception avec un FileType source et un FileType cible


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Le type de fichier source |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Le type de fichier cible |
|

### ConversionNotSupportedException(String message) {#ConversionNotSupportedException-java.lang.String-}
```
public ConversionNotSupportedException(String message)
```


Crée une instance d'exception avec un message


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message |
|

