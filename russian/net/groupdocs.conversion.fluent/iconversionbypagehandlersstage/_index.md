---
title: "IConversionByPageHandlersStage"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Упрощённый этап обработчиков конвертации по страницам. Отражение perpage для IConversionHandlersStage./iconversionhandlersstage."
type: docs
weight: 1320
url: /ru/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/
---
## IConversionByPageHandlersStage interface

Упрощённый этап обработчиков конвертации по‑странице. Перестраничное отражение [`IConversionHandlersStage`](../iconversionhandlersstage).

```csharp
public interface IConversionByPageHandlersStage : IConversionConvertOrCompress
```

## Методы

| Имя | Описание |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted)(Action&lt;ConvertedPageContext&gt;) | Регистрирует обратный вызов, который будет выполнен, когда конвертация страницы завершится успешно. Повторный вызов заменяет любой ранее установленный обработчик. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed)(Action&lt;ConvertedPageContext, Exception&gt;) | Регистрирует обратный вызов, который будет выполнен, когда конвертация страницы завершится с ошибкой. Повторный вызов заменяет любой ранее установленный обработчик. |

### См. также

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
