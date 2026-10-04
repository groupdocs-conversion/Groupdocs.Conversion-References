---
title: "TxtLoadOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры загрузки документов Txt."
type: docs
weight: 2870
url: /ru/net/groupdocs.conversion.options.load/txtloadoptions/
---
## TxtLoadOptions class

Параметры загрузки документов Txt.

```csharp
public sealed class TxtLoadOptions : LoadOptions, IPageMarginOptions, IPageSizeOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TxtLoadOptions](txtloadoptions)() | Инициализирует новый экземпляр класса [`TxtLoadOptions`](../txtloadoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/txtloadoptions/defaultfont) { get; set; } | Шрифт, используемый при отображении содержимого простого текста во время конвертации. Поскольку TXT‑файлы не содержат информацию о шрифте, это свойство указывает шрифт отображения для текстового содержимого. По умолчанию: Arial 10pt. |
| [DetectNumberingWithWhitespaces](../../groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces) { get; set; } | Позволяет указать, как распознаются элементы нумерованного списка при конвертации простого текстового документа. Значение по умолчанию: true. |
| [Encoding](../../groupdocs.conversion.options.load/txtloadoptions/encoding) { get; set; } | Получает или задает кодировку, которая будет использоваться при загрузке документа Txt. Может быть null. По умолчанию null. |
| [Format](../../groupdocs.conversion.options.load/txtloadoptions/format) { get; } | Тип файла входного документа. Имеет значение `null`, пока не установлен формат, поэтому проверяйте его на `null`, а не сравнивайте с [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), чему он никогда не равен. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |
| [LeadingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/leadingspacesoptions) { get; set; } | Получает или задает предпочтительный вариант обработки начальных пробелов. Значение по умолчанию: [`ConvertToIndent`](../txtleadingspacesoptions/converttoindent). |
| [MarginSettings](../../groupdocs.conversion.options.load/txtloadoptions/marginsettings) { get; set; } | Настройки полей страницы |
| [SizeSettings](../../groupdocs.conversion.options.load/txtloadoptions/sizesettings) { get; set; } | Настройки размера страницы |
| [TrailingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/trailingspacesoptions) { get; set; } | Получает или задает предпочтительный вариант обработки конечных пробелов. Значение по умолчанию: [`Trim`](../txttrailingspacesoptions/trim). |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### Примечания

**Font Configuration for Plain Text:**

Поскольку TXT‑файлы не содержат информацию о шрифте, используйте DefaultTextFont для указания

шрифта для отображения содержимого простого текста во время конвертации.

### См. также

* class [LoadOptions](../loadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
