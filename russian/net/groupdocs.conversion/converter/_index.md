---
title: "Converter"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Представляет основной класс, который управляет процессом конверсии документов."
type: docs
weight: 890
url: /ru/net/groupdocs.conversion/converter/
---
## Converter class

Представляет основной класс, который управляет процессом конверсии документов.

```csharp
public sealed class Converter : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | Инициализирует новый экземпляр класса [`Converter`](../converter). |
| [Converter](converter#constructor_5)(string) | Инициализирует новый экземпляр класса [`Converter`](../converter). |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Инициализирует новый экземпляр класса [`Converter`](../converter). |
| [Converter](converter#constructor_6)(string, Func&lt;ConverterSettings&gt;) | Инициализирует новый экземпляр класса [`Converter`](../converter). |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Инициализирует новый экземпляр класса [`Converter`](../converter) с явными событиями конвертации. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Инициализирует новый экземпляр класса [`Converter`](../converter). |
| [Converter](converter#constructor_7)(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Инициализирует новый экземпляр класса [`Converter`](../converter) с явными событиями конвертации. |
| [Converter](converter#constructor_8)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Инициализирует новый экземпляр класса [`Converter`](../converter). |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Инициализирует новый экземпляр класса [`Converter`](../converter) с явными событиями конвертации. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Инициализирует новый экземпляр класса [`Converter`](../converter) с явными событиями конвертации. |

## Методы

| Имя | Описание |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | Конвертирует исходный документ. Сохраняет весь преобразованный документ. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Конвертирует исходный документ. Сохраняет преобразованный документ постранично. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | Конвертирует исходный документ. Сохраняет весь преобразованный документ. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Конвертирует исходный документ. Сохраняет преобразованный документ постранично. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | Конвертирует исходный документ. Сохраняет весь преобразованный документ. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Конвертирует исходный документ. Сохраняет весь преобразованный документ. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | Конвертирует исходный документ. Сохраняет преобразованный документ постранично. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Конвертирует исходный документ. Сохраняет преобразованный документ постранично. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | Конвертирует исходный документ. Сохраняет весь преобразованный документ. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Освобождает ресурсы. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | Получает информацию о исходном документе — количество страниц и другие свойства документа, специфичные для типа файла. |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | Получает информацию о исходном документе — количество страниц и другие свойства документа, специфичные для типа файла. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Получает возможные варианты конвертации для исходного документа. |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | Проверяет, защищён ли исходный документ паролем |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Получает все поддерживаемые преобразования |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Получает поддерживаемые преобразования для указанного расширения документа |

### Примеры

**Basic conversion from file path:**

```csharp
// Конвертировать DOCX в PDF
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// Конвертировать DOCX в PDF с водяным знаком и определённым диапазоном страниц
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions
    {
        PageNumber = 1,
        PagesCount = 3,
        Watermark = new WatermarkTextOptions("CONFIDENTIAL")
        {
            Color = System.Drawing.Color.Red,
            Width = 300,
            Height = 100
        }
    };
    converter.Convert("output.pdf", options);
}
```

**Conversion from stream:**

```csharp
// Конвертировать документ из потока в поток
using (var sourceStream = File.OpenRead("sample.docx"))
using (var converter = new Converter(() => sourceStream))
using (var outputStream = File.Create("output.pdf"))
{
    var options = new PdfConvertOptions();
    converter.Convert((SaveContext context) => outputStream, options);
}
```

**Conversion with load options (password-protected document):**

```csharp
// Загрузить документ, защищённый паролем, и конвертировать в PDF
var loadOptions = new WordProcessingLoadOptions
{
    Password = "secret_password"
};
using (var converter = new Converter("protected.docx", (LoadContext context) => loadOptions))
{
    var convertOptions = new PdfConvertOptions();
    converter.Convert("output.pdf", convertOptions);
}
```

**Page-by-page conversion:**

```csharp
// Конвертировать страницы документа в отдельные файлы изображений
using (var converter = new Converter("sample.pdf"))
{
    var options = new ImageConvertOptions
    {
        Format = ImageFileType.Png
    };

    converter.Convert(
        (SavePageContext context) => File.Create($"page-{context.Page}.png"),
        options
    );
}
```

**Registering conversion event handlers (recommended path):**

```csharp
// Соберите все обработчики событий в объекте ConversionEvents и передайте его в Converter.
var events = new ConversionEvents
{
    OnDocumentConverted = ctx       => Console.WriteLine($"Done: {ctx.SourceFileName}"),
    OnDocumentFailed    = (ctx, ex) => Console.Error.WriteLine($"Conversion of {ctx.SourceFileName} failed: {ex.Message}"),
    OnPageFailed        = (ctx, ex) => Console.Error.WriteLine($"Page {ctx.Page} of {ctx.SourceFileName} failed: {ex.Message}"),
};
using (var converter = new Converter("sample.docx", () => new ConverterSettings(), () => events))
{
    converter.Convert("output.pdf", new PdfConvertOptions());
}
```

Плоские свойства `OnConversionFailed`, `OnConversionByPageFailed` и `OnCompressionCompleted` в [`ConverterSettings`](../convertersettings) по‑прежнему работают, но устарели; в новом коде следует передать экземпляр [`ConversionEvents`](../conversionevents) через параметр конструктора `events`.

**Get document information:**

```csharp
// Получить метаданные документа перед конвертацией
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### См. также

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
