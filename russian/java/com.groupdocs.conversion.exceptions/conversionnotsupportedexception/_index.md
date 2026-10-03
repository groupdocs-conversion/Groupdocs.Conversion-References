---
title: "ConversionNotSupportedException"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Исключение GroupDocs, выбрасываемое, когда конвертация из исходного файла в целевой тип файла не поддерживается"
type: docs
weight: 10
url: /ru/java/com.groupdocs.conversion.exceptions/conversionnotsupportedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class ConversionNotSupportedException extends GroupDocsConversionException
```

Исключение GroupDocs, выбрасываемое, когда конвертация из исходного файла в целевой тип файла не поддерживается

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [ConversionNotSupportedException()](#ConversionNotSupportedException--) | Конструктор по умолчанию |
|
|  | [ConversionNotSupportedException(FileType source, FileType target)](#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Создаёт экземпляр исключения с исходным типом файла FileType и целевым типом файла Filetype |
|
|  | [ConversionNotSupportedException(String message)](#ConversionNotSupportedException-java.lang.String-) | Создаёт экземпляр исключения с сообщением |
|
### ConversionNotSupportedException() {#ConversionNotSupportedException--}
```
public ConversionNotSupportedException()
```


Конструктор по умолчанию


### ConversionNotSupportedException(FileType source, FileType target) {#ConversionNotSupportedException-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionNotSupportedException(FileType source, FileType target)
```


Создаёт экземпляр исключения с исходным типом файла FileType и целевым типом файла Filetype


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Исходный тип файла |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Целевой тип файла |
|

### ConversionNotSupportedException(String message) {#ConversionNotSupportedException-java.lang.String-}
```
public ConversionNotSupportedException(String message)
```


Создаёт экземпляр исключения с сообщением


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | сообщение | java.lang.String | Сообщение |
|

