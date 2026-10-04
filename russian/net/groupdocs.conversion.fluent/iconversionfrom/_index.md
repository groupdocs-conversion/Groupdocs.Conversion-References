---
title: "IConversionFrom"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Настроить источник для конвертации"
type: docs
weight: 1440
url: /ru/net/groupdocs.conversion.fluent/iconversionfrom/
---
## IConversionFrom interface

Настроить источник для конвертации

```csharp
public interface IConversionFrom
```

## Методы

| Имя | Описание |
| --- | --- |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_1)(Func&lt;Stream&gt;) | Установить поток исходного документа |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load)(Func&lt;Stream[]&gt;) | Установить массив потоков исходных документов |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_2)(string) | Установить имя файла исходного документа |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_3)(string[]) | Установить массив исходных документов |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionfrom/withevents)(Action&lt;ConversionEvents&gt;) | Зарегистрировать обработчики событий жизненного цикла конверсии в контейнере [`ConversionEvents`](../../groupdocs.conversion/conversionevents), который существует в течение срока жизни конвертера и срабатывает при каждом запуске конверсии. Может быть вызван до или после [`WithSettings`](../iconversionsettings/withsettings). Несколько вызовов накапливаются: один и тот же внутренний контейнер передаётся каждому действию *configure*, поэтому обработчики, установленные в ранних вызовах, сохраняются, если их не перезаписать более поздним вызовом. |

### См. также

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
