---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Регистрирует обратный вызов, который будет выполнен, когда конвертация документа завершится успешно. Повторный вызов заменяет любой ранее установленный обработчик."
type: docs
weight: 10
url: /ru/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted/
---
## IConversionHandlersStage.OnConversionCompleted method

Регистрирует обратный вызов, который будет выполнен, когда конвертация документа завершится успешно. Повторный вызов заменяет любой ранее установленный обработчик.

```csharp
public IConversionHandlersStage OnConversionCompleted(Action<ConvertedContext> onCompleted)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| onCompleted | Action`1 | Действие для обработки завершения, получающее контекст конвертации. |

### Возвращаемое значение

Этот этап, поэтому дополнительные обработчики или `Convert` / `Compress` могут быть цепочкой.

### См. также

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
