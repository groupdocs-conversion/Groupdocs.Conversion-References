---
title: "WithEvents"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Зарегистрировать обработчики событий жизненного цикла конверсии в контейнере ConversionEventsgroupdocs.conversion/conversionevents, который существует в течение срока жизни конвертера и срабатывает при каждом запуске конверсии. Находится на том же этапе входа, что и WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings. При множественных вызовах происходит накопление: один и тот же внутренний контейнер передаётся каждому действию configure, поэтому обработчики, установленные в ранних вызовах, сохраняются, если не будут переопределены более поздним вызовом."
type: docs
weight: 10
url: /ru/net/groupdocs.conversion.fluent/iconversionsettings/withevents/
---
## IConversionSettings.WithEvents method

Зарегистрировать обработчики событий жизненного цикла конверсии в контейнере [`ConversionEvents`](../../../groupdocs.conversion/conversionevents), который существует в течение срока жизни конвертера и срабатывает при каждом запуске конверсии. Находится на том же этапе входа, что и [`WithSettings`](../withsettings). При множественных вызовах происходит накопление: один и тот же внутренний контейнер передаётся каждому действию *configure*, поэтому обработчики, установленные в ранних вызовах, сохраняются, если не будут переопределены более поздним вызовом.

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| configure | Action`1 | Действие, которое изменяет контейнер событий. |

### Возвращаемое значение

Этап выбора источника, чтобы `Load` можно было цепочкой вызывать.

### См. также

* interface [IConversionFrom](../../iconversionfrom)
* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionSettings](../../iconversionsettings)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
