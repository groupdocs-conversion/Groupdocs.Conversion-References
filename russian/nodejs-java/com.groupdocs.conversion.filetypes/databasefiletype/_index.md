---
title: "DatabaseFileType"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Определяет документы CAD (Computer Aided Design), которые используются для 3D графических форматов файлов и могут содержать 2D или 3D проекты."
type: docs
weight: 12
url: /ru/nodejs-java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

Определяет CAD‑документы (Computer Aided Design), которые используются для форматов файлов 3D‑графики и могут содержать 2D или 3D‑дизайны. Включает следующие типы: [Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype\#Nsf), [Log](../../com.groupdocs.conversion.filetypes/databasefiletype\#Log), [Sql](../../com.groupdocs.conversion.filetypes/databasefiletype\#Sql), Узнайте больше о форматах CAD [здесь][].


[here]: https://wiki.fileformat.com/cad
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DatabaseFileType()](#DatabaseFileType--) | Конструктор сериализации |
## Поля

| Поле | Описание |
| --- | --- |
| [Nsf](#Nsf) | Файл с расширением .nsf (Notes Storage Facility) — это формат базы данных, используемый программным обеспечением IBM Notes, ранее известным как Lotus Notes. |
| [Log](#Log) | Файл с расширением .log содержит список обычного текста с отметкой времени. |
| [Sql](#Sql) | Файл с расширением .sql — это файл Structured Query Language (SQL), содержащий код для работы с реляционными базами данных. |
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### DatabaseFileType() {#DatabaseFileType--}
```
public DatabaseFileType()
```


Конструктор сериализации

### Nsf {#Nsf}
```
public static final DatabaseFileType Nsf
```


Файл с расширением .nsf (Notes Storage Facility) — это формат базы данных, используемый программным обеспечением IBM Notes, ранее известным как Lotus Notes. Он определяет схему для хранения различных объектов, таких как электронные письма, встречи, документы, формы и представления. Узнайте больше об этом формате файла [здесь][].


[here]: https://docs.fileformat.com/database/nsf

### Log {#Log}
```
public static final DatabaseFileType Log
```


Файл с расширением .log содержит список обычного текста с отметкой времени. Обычно детали определённой активности записываются программным обеспечением или операционными системами, чтобы помочь разработчикам или пользователям отслеживать, что происходило в определённый период времени. Узнайте больше о этом формате файла [here][].


[here]: https://docs.fileformat.com/database/log

### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


Файл с расширением .sql — это файл Structured Query Language (SQL), содержащий код для работы с реляционными базами данных. Он используется для написания SQL‑запросов для операций CRUD (Create, Read, Update, and Delete) над базами данных. Узнайте больше о этом формате файла [here][].


[here]: https://docs.fileformat.com/database/sql

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Подготовлены параметры загрузки по умолчанию для исходного типа файла

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
