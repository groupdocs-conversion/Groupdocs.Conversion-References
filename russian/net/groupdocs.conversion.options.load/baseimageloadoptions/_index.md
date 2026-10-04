---
title: "BaseImageLoadOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры загрузки Image‑документов."
type: docs
weight: 2400
url: /ru/net/groupdocs.conversion.options.load/baseimageloadoptions/
---
## BaseImageLoadOptions class

Параметры загрузки Image‑документов.

```csharp
public abstract class BaseImageLoadOptions : LoadOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/baseimageloadoptions/defaultfont) { get; set; } | Шрифт по умолчанию для типов документов Psd, Emf, Wmf. Если шрифт отсутствует, будет использован следующий шрифт. |
| [Format](../../groupdocs.conversion.options.load/baseimageloadoptions/format) { get; set; } | Тип файла входного документа. Имеет значение `null`, пока не установлен формат, поэтому проверяйте его на `null`, а не сравнивайте с [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), чему он никогда не равен. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/baseimageloadoptions/resetfontfolders) { get; set; } | Сбросить папки шрифтов перед загрузкой документа |

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
