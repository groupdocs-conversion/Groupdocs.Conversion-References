---
title: "FluentConverter"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Класс для fluent‑настройки конверсии."
type: docs
weight: 1580
url: /ru/net/groupdocs.conversion/fluentconverter/
---
## FluentConverter class

Класс для fluent‑настройки конверсии.

```csharp
public static class FluentConverter
```

## Методы

| Имя | Описание |
| --- | --- |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_1)(Func&lt;Stream&gt;) | Настройте поток исходного документа |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load)(Func&lt;Stream[]&gt;) | Настройте набор потоков исходных документов |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_2)(string) | Настройте исходный документ для конвертации |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_3)(string[]) | Настройте набор исходных документов |
| static [WithEvents](../../groupdocs.conversion/fluentconverter/withevents)(Action&lt;ConversionEvents&gt;) | Вариант цепочки fluent на этапе входа, который начинается с обработчиков событий жизненного цикла конвертации. Находится на том же этапе входа, что и [`WithSettings`](./withsettings), и полученный пакет [`ConversionEvents`](../conversionevents) срабатывает при каждом запуске конвертации конвертером. |
| static [WithSettings](../../groupdocs.conversion/fluentconverter/withsettings)(Func&lt;ConverterSettings&gt;) | Настройте параметры конвертации |

### Примечания

Пример использования fluent конвертации:

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// Рекомендуется: агрегировать обработчики через WithEvents на раннем этапе (до Load).
FluentConverter
    .WithEvents(e =>
    {
        e.OnDocumentConverted = ctx       => Console.WriteLine($"Done: {ctx.SourceFileName}");
        e.OnDocumentFailed    = (ctx, ex) => Console.Error.WriteLine(ex.Message);
    })
    .Load("input.docx")
    .ConvertTo("output.pdf").WithOptions(new PdfConvertOptions())
    .Convert();
```

```csharp
// Зеркало по страницам: обработчики по страницам через WithEvents на раннем этапе.
FluentConverter
    .WithEvents(e =>
    {
        e.OnPageConverted = ctx       => Console.WriteLine($"page {ctx.Page} done");
        e.OnPageFailed    = (ctx, ex) => Console.Error.WriteLine($"page {ctx.Page}: {ex.Message}");
    })
    .Load("input.pdf")
    .ConvertByPageTo(ctx => new FileStream($"page-{ctx.Page}.png", FileMode.Create))
    .WithOptions(new ImageConvertOptions { Format = ImageFileType.Png })
    .Convert();
```

```csharp
// Унаследованная цепочка всё ещё компилируется без изменений (теперь поддерживается устаревшими поэтапными интерфейсами):
FluentConverter.WithSettings(() => new ConverterSettings())
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertTo("").WithOptions(new PdfConvertOptions())
    .OnConversionCompleted(convertedDocumentStream => { })
    .Convert();
```

```csharp
FluentConverter.Load("").GetPossibleConversions();
FluentConverter.Load("").GetDocumentInfo();
FluentConverter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions();
FluentConverter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();
```

### См. также

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
