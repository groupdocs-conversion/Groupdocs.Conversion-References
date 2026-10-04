---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Получить поток конвертированной страницы. Будет вызвано только если установлен ConvertToconvertedStreamProvider."
type: docs
weight: 10
url: /ru/net/groupdocs.conversion.fluent/iconversionbypagecompleted/onconversioncompleted/
---
## IConversionByPageCompleted.OnConversionCompleted method

Получить поток конвертированной страницы. Будет вызвано только если "ConvertTo(convertedStreamProvider)" установлен.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedPageContext> convertedPageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| convertedPageStream | Action`1 | Поставщик потока конвертированной страницы [`ConvertedPageContext`](../../../groupdocs.conversion/convertedpagecontext) |

### Возвращаемое значение

Интерфейс для продолжения построения конвертации

### См. также

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageCompleted](../../iconversionbypagecompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
