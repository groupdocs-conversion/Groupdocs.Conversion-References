---
title: "ConversionNotSupportedException"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Excepción de GroupDocs lanzada cuando la conversión del archivo de origen al tipo de archivo de destino no es compatible"
type: docs
weight: 10
url: /es/java/com.groupdocs.conversion.exceptions/conversionnotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class ConversionNotSupportedException extends GroupDocsConversionException
```

Excepción de GroupDocs lanzada cuando la conversión del archivo de origen al tipo de archivo de destino no es compatible

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ConversionNotSupportedException()](#ConversionNotSupportedException--) | Constructor predeterminado |
|
|  | [ConversionNotSupportedException(FileType source, FileType target)](#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Crea una instancia de excepción con un FileType de origen y un FileType de destino |
|
|  | [ConversionNotSupportedException(String message)](#ConversionNotSupportedException-java.lang.String-) | Crea una instancia de excepción con un mensaje |
|
### ConversionNotSupportedException() {#ConversionNotSupportedException--}
```
public ConversionNotSupportedException()
```


Constructor predeterminado


### ConversionNotSupportedException(FileType source, FileType target) {#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionNotSupportedException(FileType source, FileType target)
```


Crea una instancia de excepción con un FileType de origen y un FileType de destino


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | El tipo de archivo de origen |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | El tipo de archivo de destino |
|

### ConversionNotSupportedException(String message) {#ConversionNotSupportedException-java.lang.String-}
```
public ConversionNotSupportedException(String message)
```


Crea una instancia de excepción con un mensaje


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | mensaje | java.lang.String | El mensaje |
|

