---
title: "IConversionHandlersStage"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Плоский этап обработчиков конвертации. Позволяет задавать OnConversionCompleted или OnConversionFailed в любом порядке и любое количество раз перед переходом к Convert / Compress. События следует регистрировать на раннем этапе через WithEvents./iconversionsettings/withevents вместо этого этапа."
type: docs
weight: 1480
url: /ru/net/groupdocs.conversion.fluent/iconversionhandlersstage/
---
## IConversionHandlersStage interface

Плоский этап обработчиков конвертации. Позволяет задавать `OnConversionCompleted` или `OnConversionFailed` в любом порядке и любое количество раз перед переходом к `Convert` / `Compress`. События следует регистрировать на раннем этапе через [`WithEvents`](../iconconversionsettings/withevents) вместо этого этапа.

```csharp
public interface IConversionHandlersStage : IConversionConvertOrCompress
```

## Методы

| Имя | Описание |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted)(Action&lt;ConvertedContext&gt;) | Регистрирует обратный вызов, который будет выполнен, когда конвертация документа завершится успешно. Повторный вызов заменяет любой ранее установленный обработчик. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed)(Action&lt;ConvertedContext, Exception&gt;) | Регистрирует обратный вызов, который будет выполнен, когда конвертация документа завершится с ошибкой. Повторный вызов заменяет любой ранее установленный обработчик. |

### См. также

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
