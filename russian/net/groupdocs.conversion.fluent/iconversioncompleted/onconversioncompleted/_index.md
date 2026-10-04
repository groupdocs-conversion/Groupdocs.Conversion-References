---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Получить поток конвертированного документа. Событие будет вызвано только если установлен ConvertTostring fileName или ConvertToconvertedStreamProvider."
type: docs
weight: 10
url: /ru/net/groupdocs.conversion.fluent/iconversioncompleted/onconversioncompleted/
---
## IConversionCompleted.OnConversionCompleted method

Получает поток конвертированного документа. Будет вызвано только если "ConvertTo(string fileName)" или ConvertTo(convertedStreamProvider)" установлен.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedContext> convertedFileStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| convertedFileStream | Action`1 | Поставщик потока конвертированного документа [`ConvertedContext`](../../../groupdocs.conversion/convertedcontext) |

### Возвращаемое значение

Интерфейс для продолжения построения конвертации

### См. также

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionCompleted](../../iconversioncompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
