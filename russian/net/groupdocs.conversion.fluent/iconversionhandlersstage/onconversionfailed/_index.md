---
title: "OnConversionFailed"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Регистрирует обратный вызов, который будет выполнен, когда конвертация документа завершится с ошибкой. Повторный вызов заменяет любой ранее установленный обработчик."
type: docs
weight: 20
url: /ru/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed/
---
## IConversionHandlersStage.OnConversionFailed method

Регистрирует обратный вызов, который будет выполнен, когда конвертация документа завершится с ошибкой. Повторный вызов заменяет любой ранее установленный обработчик.

```csharp
public IConversionHandlersStage OnConversionFailed(Action<ConvertedContext, Exception> onFailed)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| onFailed | Action`2 | Действие для обработки ошибки, получающее контекст конвертации и исключение, вызвавшее ошибку. |

### Возвращаемое значение

Этот этап, поэтому дополнительные обработчики или `Convert` / `Compress` могут быть цепочкой.

### См. также

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
