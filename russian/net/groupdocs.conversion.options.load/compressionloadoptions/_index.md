---
title: CompressionLoadOptions
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Параметры загрузки сжатых документов.
type: docs
weight: 1850
url: /ru/net/groupdocs.conversion.options.load/compressionloadoptions/
---
## CompressionLoadOptions class

Параметры загрузки сжатых документов.

```csharp
public sealed class CompressionLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CompressionLoadOptions](compressionloadoptions)() | Инициализирует новый экземпляр[`CompressionLoadOptions`](../compressionloadoptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/compressionloadoptions/convertowned) { get; } | Параметр, определяющий необходимость преобразования собственных документов в контейнере документов |
| [ConvertOwner](../../groupdocs.conversion.options.load/compressionloadoptions/convertowner) { get; } | Параметр, определяющий необходимость преобразования самого контейнера документов Если это свойство равно true, контейнер документов будет первым преобразованным document |
| [Depth](../../groupdocs.conversion.options.load/compressionloadoptions/depth) { get; set; } | Опция для управления количеством уровней глубины для выполнения преобразования |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |
| [Password](../../groupdocs.conversion.options.load/compressionloadoptions/password) { get; set; } | Установить пароль для загрузки защищенного документа. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит хеш-функцией по умолчанию. |

### Смотрите также

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* пространство имен [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->