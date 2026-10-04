---
title: "OnConversionFailed"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Регистрирует обратный вызов, который будет выполнен, когда конверсия страницы завершается с ошибкой. Повторный вызов заменяет любой ранее установленный обработчик."
type: docs
weight: 20
url: /ru/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed/
---
## IConversionByPageHandlersStage.OnConversionFailed method

Регистрирует обратный вызов, который будет выполнен, когда конвертация страницы завершится с ошибкой. Повторный вызов заменяет любой ранее установленный обработчик.

```csharp
public IConversionByPageHandlersStage OnConversionFailed(
    Action<ConvertedPageContext, Exception> onFailed)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| onFailed | Action`2 | Действие для обработки ошибки, получающее контекст конвертированной страницы и исключение, вызвавшее ошибку. |

### Возвращаемое значение

Этот этап, поэтому дополнительные обработчики или `Convert` / `Compress` могут быть цепочкой.

### См. также

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
