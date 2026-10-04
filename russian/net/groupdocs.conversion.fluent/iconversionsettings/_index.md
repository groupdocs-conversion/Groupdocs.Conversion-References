---
title: "IConversionSettings"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Настройте параметры конвертации или события на этапе входа перед Load."
type: docs
weight: 1540
url: /ru/net/groupdocs.conversion.fluent/iconversionsettings/
---
## IConversionSettings interface

Настройте параметры конвертации или события на этапе входа (до `Load`).

```csharp
public interface IConversionSettings
```

## Методы

| Имя | Описание |
| --- | --- |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionsettings/withevents)(Action&lt;ConversionEvents&gt;) | Зарегистрируйте обработчики событий жизненного цикла конвертации в контейнере [`ConversionEvents`](../../groupdocs.conversion/conversionevents), который существует в течение срока жизни конвертера и срабатывает при каждом запуске конвертации. Он находится на том же этапе входа, что и [`WithSettings`](./withsettings). Несколько вызовов накапливаются: один и тот же внутренний контейнер передаётся каждому действию *configure*, поэтому обработчики, установленные в более ранних вызовах, сохраняются, если их не перезаписать более поздним вызовом. |
| [WithSettings](../../groupdocs.conversion.fluent/iconversionsettings/withsettings)(Func&lt;ConverterSettings&gt;) | Установите параметры конвертера |

### См. также

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
