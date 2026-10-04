---
title: "Compress"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Вызовите этот метод, чтобы сжать результаты конвертации. Зарегистрируйте обработчик compressedstream на этапе входа через WithEventsgroupdocs.conversion.fluent/iconversionsettings/withevents, параметр OnCompressionCompleted."
type: docs
weight: 10
url: /ru/net/groupdocs.conversion.fluent/iconversioncompressresult/compress/
---
## IConversionCompressResult.Compress method

Вызовите этот метод, чтобы сжать результаты конвертации. Зарегистрируйте обработчик compressed-stream на этапе входа через [`WithEvents`](../../iconversionsettings/withevents) (параметр `OnCompressionCompleted`).

```csharp
public IConversionCompressResultCompletedOrConvert Compress(CompressionConvertOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| опции | CompressionConvertOptions | Параметры сжатия конвертации |

### Возвращаемое значение

Продолжение, которое переходит к `Convert`.

### См. также

* interface [IConversionCompressResultCompletedOrConvert](../../iconversioncompressresultcompletedorconvert)
* class [CompressionConvertOptions](../../../groupdocs.conversion.options.convert/compressionconvertoptions)
* interface [IConversionCompressResult](../../iconversioncompressresult)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
