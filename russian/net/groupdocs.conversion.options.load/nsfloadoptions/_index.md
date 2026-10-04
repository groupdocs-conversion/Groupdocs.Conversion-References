---
title: "NsfLoadOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры загрузки Nsf‑документов."
type: docs
weight: 2690
url: /ru/net/groupdocs.conversion.options.load/nsfloadoptions/
---
## NsfLoadOptions class

Параметры загрузки Nsf‑документов.

```csharp
public sealed class NsfLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [NsfLoadOptions](nsfloadoptions)() | Инициализирует новый экземпляр класса [`NsfLoadOptions`](../nsfloadoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/nsfloadoptions/convertowned) { get; } | Реализует [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) только для чтения. Установлено в true. Принадлежащие документы будут конвертированы. |
| [ConvertOwner](../../groupdocs.conversion.options.load/nsfloadoptions/convertowner) { get; } | Реализует [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) только для чтения. Установлено в false. Владелец не будет конвертирован. |
| [Depth](../../groupdocs.conversion.options.load/nsfloadoptions/depth) { get; set; } | Реализует [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). По умолчанию: 3. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/nsfloadoptions/clone)() | Клонирует текущий экземпляр. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
