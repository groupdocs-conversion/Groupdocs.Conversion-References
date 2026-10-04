---
title: "WithEvents"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Зарегистрировать обработчики событий жизненного цикла конвертации в контейнере ConversionEventsgroupdocs.conversion/conversionevents, который существует в течение срока жизни конвертера и срабатывает при каждом запуске конвертации. Может быть вызван до или после WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings. При множественных вызовах происходит накопление: один и тот же внутренний контейнер передаётся каждому действию configure, поэтому обработчики, установленные в ранних вызовах, сохраняются, если их не перезаписать более поздним вызовом."
type: docs
weight: 20
url: /ru/net/groupdocs.conversion.fluent/iconversionfrom/withevents/
---
## IConversionFrom.WithEvents method

Зарегистрировать обработчики событий жизненного цикла конвертации в контейнере [`ConversionEvents`](../../../groupdocs.conversion/conversionevents), который существует в течение срока жизни конвертера и срабатывает при каждом запуске конвертации. Может быть вызван до или после [`WithSettings`](../../iconversionsettings/withsettings). При множественных вызовах происходит накопление: один и тот же внутренний контейнер передаётся каждому действию *configure*, поэтому обработчики, установленные в ранних вызовах, сохраняются, если их не перезаписать более поздним вызовом.

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| configure | Action`1 | Действие, которое изменяет контейнер событий. |

### Возвращаемое значение

Этот этап, чтобы дальнейшие вызовы начального этапа или `Load` могли быть цепочкой.

### См. также

* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
