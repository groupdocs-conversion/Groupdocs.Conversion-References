---
title: "MarkdownOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры конвертации в тип файла markdown."
type: docs
weight: 2010
url: /ru/net/groupdocs.conversion.options.convert/markdownoptions/
---
## MarkdownOptions class

Параметры конвертации в тип файла markdown.

```csharp
public sealed class MarkdownOptions : ValueObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MarkdownOptions](markdownoptions)() | Инициализирует новый экземпляр класса [`MarkdownOptions`](../markdownoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.conversion.options.convert/markdownoptions/exportimagesasbase64) { get; set; } | Экспортировать изображения в виде base64. По умолчанию true. Игнорируется, когда установлен [`ImageSavingCallback`](./imagesavingcallback). |
| [ImageSavingCallback](../../groupdocs.conversion.options.convert/markdownoptions/imagesavingcallback) { get; set; } | Обратный вызов вызывается один раз для каждого изображения при сохранении Markdown. Позволяет вызывающему сохранять изображения внешне и заменять URI, встроенный в документ. Имеет приоритет над [`ExportImagesAsBase64`](./exportimagesasbase64), если не null. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
