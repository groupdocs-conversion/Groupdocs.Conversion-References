---
title: "CorruptOrDamagedFileException"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Исключение GroupDocs, выбрасываемое, когда файл повреждён или испорчен"
type: docs
weight: 11
url: /ru/java/com.groupdocs.conversion.exceptions/corruptordamagedfileexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.groupdocs.conversion.exceptions.GroupDocsConversionException](../../com.groupdocs.conversion.exceptions/groupdocsconversionexception)
```
public final class CorruptOrDamagedFileException extends GroupDocsConversionException
```

Исключение GroupDocs, выбрасываемое, когда файл повреждён или испорчен

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [CorruptOrDamagedFileException()](#CorruptOrDamagedFileException--) | Конструктор по умолчанию |
|
|  | [CorruptOrDamagedFileException(FileType fileType)](#CorruptOrDamagedFileException-com.groupdocs.conversion.filetypes.FileType-) | Создаёт экземпляр исключения с типом файла |
|
|  | [CorruptOrDamagedFileException(String message)](#CorruptOrDamagedFileException-java.lang.String-) | Создаёт экземпляр исключения с сообщением |
|
|  | [CorruptOrDamagedFileException(String message, RuntimeException exception)](#CorruptOrDamagedFileException-java.lang.String-java.lang.RuntimeException-) | Создаёт экземпляр исключения с сообщением и передаёт внутреннее исключение |
|
### CorruptOrDamagedFileException() {#CorruptOrDamagedFileException--}
```
public CorruptOrDamagedFileException()
```


Конструктор по умолчанию


### CorruptOrDamagedFileException(FileType fileType) {#CorruptOrDamagedFileException-com.groupdocs.conversion.filetypes.FileType-}
```
public CorruptOrDamagedFileException(FileType fileType)
```


Создаёт экземпляр исключения с типом файла


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Тип файла |
|

### CorruptOrDamagedFileException(String message) {#CorruptOrDamagedFileException-java.lang.String-}
```
public CorruptOrDamagedFileException(String message)
```


Создаёт экземпляр исключения с сообщением


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | сообщение | java.lang.String | Сообщение |
|

### CorruptOrDamagedFileException(String message, RuntimeException exception) {#CorruptOrDamagedFileException-java.lang.String-java.lang.RuntimeException-}
```
public CorruptOrDamagedFileException(String message, RuntimeException exception)
```


Создаёт экземпляр исключения с сообщением и передаёт внутреннее исключение


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | сообщение | java.lang.String | Сообщение |
|
|  | исключение | java.lang.RuntimeException | Внутреннее исключение |
|

