---
title: "CadLoadOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры загрузки CAD‑документов."
type: docs
weight: 2430
url: /ru/net/groupdocs.conversion.options.load/cadloadoptions/
---
## CadLoadOptions class

Параметры загрузки CAD‑документов.

```csharp
public sealed class CadLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CadLoadOptions](cadloadoptions)() | Инициализирует новый экземпляр класса [`CadLoadOptions`](../cadloadoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/cadloadoptions/backgroundcolor) { get; set; } | Получает или задает цвет фона. |
| [CtbSources](../../groupdocs.conversion.options.load/cadloadoptions/ctbsources) { get; set; } | Получает или задает источники CTB. |
| [DrawColor](../../groupdocs.conversion.options.load/cadloadoptions/drawcolor) { get; set; } | Получает или задает цвет переднего плана. |
| [DrawType](../../groupdocs.conversion.options.load/cadloadoptions/drawtype) { get; set; } | Получает или задает тип чертежа. |
| [Format](../../groupdocs.conversion.options.load/cadloadoptions/format) { get; set; } | Тип файла входного документа. Имеет значение `null`, пока не установлен формат, поэтому проверяйте его на `null`, а не сравнивайте с [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), чему он никогда не равен. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |
| [LayoutNames](../../groupdocs.conversion.options.load/cadloadoptions/layoutnames) { get; set; } | Указывает, какие макеты CAD следует преобразовать |
| [LayoutScope](../../groupdocs.conversion.options.load/cadloadoptions/layoutscope) { get; set; } | Получает или задает, какие пространства чертежа преобразуются. По умолчанию — [`Both`](../cadlayoutscope/both), что не ограничивает преобразование. Игнорируется, когда указаны [`LayoutNames`](./layoutnames), поскольку явные имена макетов всегда имеют приоритет. Значение `null` рассматривается как [`Both`](../cadlayoutscope/both). |

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
