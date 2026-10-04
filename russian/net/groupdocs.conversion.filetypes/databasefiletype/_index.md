---
title: "DatabaseFileType"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет документы баз данных. Включает следующие типы файлов Nsf./databasefiletype/nsfLog./databasefiletype/logSql./databasefiletype/sql"
type: docs
weight: 1090
url: /ru/net/groupdocs.conversion.filetypes/databasefiletype/
---
## DatabaseFileType class

Определяет документы баз данных. Включает следующие типы файлов: [`Nsf`](./nsf)[`Log`](./log)[`Sql`](./sql)

```csharp
public sealed class DatabaseFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DatabaseFileType](databasefiletype)() | Конструктор сериализации |

## Свойства

| Имя | Описание |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Описание типа файла |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Расширение файла |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Семейство файлов |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Формат файла |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Сравнивает текущий объект с другим. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Реализует [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит функцией хеширования по умолчанию. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Строковое представление |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Log](../../groupdocs.conversion.filetypes/databasefiletype/log) | Файл с расширением .log содержит список обычного текста с отметкой времени. Обычно детали определённой активности записываются программным обеспечением или операционными системами, чтобы помочь разработчикам или пользователям отслеживать, что происходило в определённый период времени. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/database/log). |
| static readonly [Nsf](../../groupdocs.conversion.filetypes/databasefiletype/nsf) | Файл с расширением .nsf (Notes Storage Facility) — это формат файлов базы данных, используемый программным обеспечением IBM Notes, ранее известным как Lotus Notes. Он определяет схему для хранения различных объектов, таких как электронные письма, встречи, документы, формы и представления. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/database/nsf). |
| static readonly [Sql](../../groupdocs.conversion.filetypes/databasefiletype/sql) | Файл с расширением .sql — это файл Structured Query Language (SQL), содержащий код для работы с реляционными базами данных. Он используется для написания SQL‑запросов для операций CRUD (Create, Read, Update, Delete) с базами данных. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/database/sql). |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
