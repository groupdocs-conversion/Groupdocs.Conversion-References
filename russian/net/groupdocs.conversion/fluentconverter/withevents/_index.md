---
title: "WithEvents"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Вариант начального этапа fluent chain, который начинается с обработчиков событий жизненного цикла конверсии. Находится на том же начальном этапе, что и WithSettingsgroupdocs.conversion/fluentconverter/withsettings, и результирующий ConversionEventsgroupdocs.conversion/conversionevents bag срабатывает при каждом запуске конвертации конвертером."
type: docs
weight: 20
url: /ru/net/groupdocs.conversion/fluentconverter/withevents/
---
## FluentConverter.WithEvents method

Вариант начального этапа fluent chain, который начинается с обработчиков событий жизненного цикла конверсии. Находится на том же начальном этапе, что и [`WithSettings`](../withsettings), и результирующий [`ConversionEvents`](../../conversionevents) bag срабатывает при каждом запуске конвертации конвертером.

```csharp
public static IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| configure | Action`1 | Действие, которое изменяет контейнер событий. |

### Возвращаемое значение

Этап выбора источника, чтобы `Load` можно было цепочкой вызывать.

### См. также

* interface [IConversionFrom](../../../groupdocs.conversion.fluent/iconversionfrom)
* class [ConversionEvents](../../conversionevents)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
