---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Регистрирует обратный вызов, который будет выполнен, когда конверсия страницы завершается успешно. Повторный вызов заменяет любой ранее установленный обработчик."
type: docs
weight: 10
url: /ru/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted/
---
## IConversionByPageHandlersStage.OnConversionCompleted method

Регистрирует обратный вызов, который будет выполнен, когда конвертация страницы завершится успешно. Повторный вызов заменяет любой ранее установленный обработчик.

```csharp
public IConversionByPageHandlersStage OnConversionCompleted(
    Action<ConvertedPageContext> onCompleted)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| onCompleted | Action`1 | Действие для обработки завершения, получающее контекст конвертированной страницы. |

### Возвращаемое значение

Этот этап, поэтому дополнительные обработчики или `Convert` / `Compress` могут быть цепочкой.

### См. также

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
