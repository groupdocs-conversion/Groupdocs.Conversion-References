---
title: "GisLoadOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры загрузки GIS‑документов."
type: docs
weight: 2540
url: /ru/net/groupdocs.conversion.options.load/gisloadoptions/
---
## GisLoadOptions class

Параметры загрузки GIS‑документов.

```csharp
public class GisLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GisLoadOptions](gisloadoptions)() | Инициализирует новый экземпляр класса [`GisLoadOptions`](../gisloadoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gisloadoptions/format) { get; set; } | Тип файла входного документа. Имеет значение `null`, пока не установлен формат, поэтому проверяйте его на `null`, а не сравнивайте с [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), чему он никогда не равен. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | Устанавливает желаемую высоту страницы при конвертации GIS‑документа. Значение по умолчанию — 1000. |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | Устанавливает желаемую ширину страницы при конвертации GIS‑документа. Значение по умолчанию — 1000. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
