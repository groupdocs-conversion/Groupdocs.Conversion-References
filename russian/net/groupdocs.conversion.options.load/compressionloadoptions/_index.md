---
title: "CompressionLoadOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры загрузки документов сжатия."
type: docs
weight: 2440
url: /ru/net/groupdocs.conversion.options.load/compressionloadoptions/
---
## CompressionLoadOptions class

Параметры загрузки документов сжатия.

```csharp
public sealed class CompressionLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CompressionLoadOptions](compressionloadoptions)() | Инициализирует новый экземпляр класса [`CompressionLoadOptions`](../compressionloadoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/compressionloadoptions/convertowned) { get; } | Реализует [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) только для чтения. Установлено в true. Принадлежащие документы будут конвертированы. |
| [ConvertOwner](../../groupdocs.conversion.options.load/compressionloadoptions/convertowner) { get; } | Реализует [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) только для чтения. Установлено в false. Владелец не будет конвертирован. |
| [Depth](../../groupdocs.conversion.options.load/compressionloadoptions/depth) { get; set; } | Реализует [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). По умолчанию: 3. |
| [Format](../../groupdocs.conversion.options.load/compressionloadoptions/format) { get; set; } | Тип файла входного документа. Имеет значение `null`, пока не установлен формат, поэтому проверяйте его на `null`, а не сравнивайте с [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), чему он никогда не равен. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |
| [Password](../../groupdocs.conversion.options.load/compressionloadoptions/password) { get; set; } | Установите пароль для загрузки защищённого документа. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
