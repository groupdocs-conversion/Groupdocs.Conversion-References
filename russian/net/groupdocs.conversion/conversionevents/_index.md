---
title: "ConversionEvents"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Объединяет обработчики событий жизненного цикла конвертации. Передайте экземпляр в параметр events конструкторов Converter./converter или в метод WithEvents в стиле fluent. Предпочтительно использовать это вместо отдельных свойств обработчиков ConverterSettings./convertersettings, которые устарели."
type: docs
weight: 850
url: /ru/net/groupdocs.conversion/conversionevents/
---
## ConversionEvents class

Объединяет обработчики событий жизненного цикла конвертации. Передайте экземпляр в параметр `events` конструктора [`Converter`](../converter) или в метод `WithEvents` в стиле fluent. Предпочтительно использовать это вместо отдельных свойств обработчиков [`ConverterSettings`](../convertersettings), которые устарели.

```csharp
public sealed class ConversionEvents
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ConversionEvents](conversionevents)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [OnCompressionCompleted](../../groupdocs.conversion/conversionevents/oncompressioncompleted) { get; set; } | Срабатывает, когда сжатие вывода конвертации завершается. Вызывается только в сборках, включающих конвейер сжатия (LIB_ZIP). |
| [OnConversionCompleted](../../groupdocs.conversion/conversionevents/onconversioncompleted) { get; set; } | Срабатывает один раз, когда процесс конвертации завершается, независимо от успеха или неудачи. |
| [OnConversionProgress](../../groupdocs.conversion/conversionevents/onconversionprogress) { get; set; } | Срабатывает периодически, показывая прогресс конвертации в процентах (0–100). |
| [OnConversionStarted](../../groupdocs.conversion/conversionevents/onconversionstarted) { get; set; } | Срабатывает один раз в начале процесса конвертации, до обработки любого документа. |
| [OnDocumentConverted](../../groupdocs.conversion/conversionevents/ondocumentconverted) { get; set; } | Срабатывает один раз для каждой полной конвертации документа, завершившейся успешно. |
| [OnDocumentFailed](../../groupdocs.conversion/conversionevents/ondocumentfailed) { get; set; } | Срабатывает один раз для каждой полной конвертации документа, завершившейся с ошибкой. |
| [OnFontSubstituted](../../groupdocs.conversion/conversionevents/onfontsubstituted) { get; set; } | Срабатывает, когда шрифт, указанный в исходном документе, недоступен и заменяется (либо правилом [`FontSubstitute`](../../groupdocs.conversion.contracts/fontsubstitute), предоставленным клиентом, либо настроенным шрифтом по умолчанию, либо внутренним резервным шрифтом конвейера конвертации). |
| [OnPageConverted](../../groupdocs.conversion/conversionevents/onpageconverted) { get; set; } | Срабатывает один раз для каждой страницы, когда постраничная конвертация завершается успешно. |
| [OnPageFailed](../../groupdocs.conversion/conversionevents/onpagefailed) { get; set; } | Срабатывает один раз для каждой страницы, когда постраничная конвертация завершается с ошибкой. |

### См. также

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
