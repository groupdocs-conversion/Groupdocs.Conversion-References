---
title: "NoteLoadOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры загрузки One‑документов."
type: docs
weight: 2680
url: /ru/net/groupdocs.conversion.options.load/noteloadoptions/
---
## NoteLoadOptions class

Параметры загрузки One‑документов.

```csharp
public sealed class NoteLoadOptions : LoadOptions, IFontSubstituteLoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [NoteLoadOptions](noteloadoptions)() | Инициализирует новый экземпляр класса [`NoteLoadOptions`](../noteloadoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/noteloadoptions/defaultfont) { get; set; } | Шрифт по умолчанию для документа Note. Следующий шрифт будет использован, если требуемый шрифт отсутствует. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/noteloadoptions/fontsubstitutes) { get; set; } | Заменять определённые шрифты при конвертации документа Note. |
| [Format](../../groupdocs.conversion.options.load/noteloadoptions/format) { get; } | Тип файла входного документа. Имеет значение `null`, пока не установлен формат, поэтому проверяйте его на `null`, а не сравнивайте с [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), чему он никогда не равен. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |
| [Password](../../groupdocs.conversion.options.load/noteloadoptions/password) { get; set; } | Устанавливает пароль для снятия защиты с защищённого документа. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [LoadOptions](../loadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
