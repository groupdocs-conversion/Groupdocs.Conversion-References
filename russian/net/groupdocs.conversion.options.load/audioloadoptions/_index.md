---
title: "AudioLoadOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры загрузки аудио‑документов."
type: docs
weight: 2390
url: /ru/net/groupdocs.conversion.options.load/audioloadoptions/
---
## AudioLoadOptions class

Параметры загрузки аудио‑документов.

```csharp
public sealed class AudioLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AudioLoadOptions](audioloadoptions)() | Инициализирует новый экземпляр класса [`AudioLoadOptions`](../audioloadoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/audioloadoptions/format) { get; set; } | Тип файла входного документа. Имеет значение `null`, пока не установлен формат, поэтому проверяйте его на `null`, а не сравнивайте с [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), чему он никогда не равен. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |
| [SetAudioConnector](../../groupdocs.conversion.options.load/audioloadoptions/setaudioconnector)(IAudioConnector) | Установить соединитель аудио‑документа |

### См. также

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
