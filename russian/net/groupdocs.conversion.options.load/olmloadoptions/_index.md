---
title: "OlmLoadOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры загрузки документов Olm."
type: docs
weight: 2700
url: /ru/net/groupdocs.conversion.options.load/olmloadoptions/
---
## OlmLoadOptions class

Параметры загрузки документов Olm.

```csharp
public sealed class OlmLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [OlmLoadOptions](olmloadoptions)() | Инициализирует новый экземпляр класса [`OlmLoadOptions`](../olmloadoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/olmloadoptions/convertowned) { get; } | Реализует [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) только для чтения. Установлено в true. Принадлежащие документы будут конвертированы. |
| [ConvertOwner](../../groupdocs.conversion.options.load/olmloadoptions/convertowner) { get; } | Реализует [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) только для чтения. Установлено в false. Владелец не будет конвертирован. |
| [Depth](../../groupdocs.conversion.options.load/olmloadoptions/depth) { get; set; } | Реализует [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). По умолчанию: 3. |
| [Folder](../../groupdocs.conversion.options.load/olmloadoptions/folder) { get; set; } | Папка, которая будет обрабатываться. По умолчанию: Inbox. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/olmloadoptions/clone)() | Клонирует текущий экземпляр. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
