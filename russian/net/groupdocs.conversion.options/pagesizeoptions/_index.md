---
title: "PageSizeOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Представляет параметры, поддерживающие размер страницы."
type: docs
weight: 2990
url: /ru/net/groupdocs.conversion.options/pagesizeoptions/
---
## PageSizeOptions class

Представляет параметры, поддерживающие размер страницы.

```csharp
public sealed class PageSizeOptions : ValueObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PageSizeOptions](pagesizeoptions)() | Конструктор по умолчанию. Инициализирует [`PageSize`](./pagesize) значением [`Unset`](../pagesize/unset). |

## Свойства

| Имя | Описание |
| --- | --- |
| [PageHeight](../../groupdocs.conversion.options/pagesizeoptions/pageheight) { get; set; } | Высота страницы в пунктах, применяемая перед конвертацией. При установке, [`PageSize`](./pagesize) автоматически меняется на [`Custom`](../pagesize/custom). |
| [PageSize](../../groupdocs.conversion.options/pagesizeoptions/pagesize) { get; set; } | Реализует [`PageSize`](../pagesize) |
| [PageWidth](../../groupdocs.conversion.options/pagesizeoptions/pagewidth) { get; set; } | Ширина страницы в пунктах, применяемая перед конвертацией. При установке, [`PageSize`](./pagesize) автоматически меняется на [`Custom`](../pagesize/custom). |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options](../../groupdocs.conversion.options)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
