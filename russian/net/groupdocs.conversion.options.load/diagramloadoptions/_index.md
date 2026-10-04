---
title: "DiagramLoadOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры загрузки Diagram‑документов."
type: docs
weight: 2470
url: /ru/net/groupdocs.conversion.options.load/diagramloadoptions/
---
## DiagramLoadOptions class

Параметры загрузки Diagram‑документов.

```csharp
public sealed class DiagramLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DiagramLoadOptions](diagramloadoptions)() | Инициализирует новый экземпляр класса [`DiagramLoadOptions`](../diagramloadoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/diagramloadoptions/defaultfont) { get; set; } | Шрифт по умолчанию для документа Diagram. Следующий шрифт будет использоваться, если шрифт отсутствует. |
| [Format](../../groupdocs.conversion.options.load/diagramloadoptions/format) { get; set; } | Тип файла входного документа. Имеет значение `null`, пока не установлен формат, поэтому проверяйте его на `null`, а не сравнивайте с [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), чему он никогда не равен. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |

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
