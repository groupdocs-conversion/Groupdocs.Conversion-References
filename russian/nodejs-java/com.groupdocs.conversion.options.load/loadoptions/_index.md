---
title: "LoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Абстрактный класс параметров загрузки документа."
type: docs
weight: 25
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public abstract class LoadOptions extends ValueObject implements Serializable
```

Абстрактный класс параметров загрузки документа.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) | Тип файла входного документа |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Тип файла входного документа |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Тип файла входного документа

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Тип файла входного документа

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

