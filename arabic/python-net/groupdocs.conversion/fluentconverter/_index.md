---
title: "فئة FluentConverter"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يمثل إعداد تحويل سلس."
type: docs
url: /ar/python-net/groupdocs.conversion/fluentconverter/
is_root: false
weight: 120
---


## FluentConverter class

يمثل إعداد تحويل سلس.

مثال على استخدام التحويل السلس:

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// موصى به: تجميع المعالجات عبر WithEvents في المرحلة المبكرة (قبل Load).
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
// مرآة لكل صفحة: معالجات لكل صفحة عبر WithEvents في المرحلة المبكرة.
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
// السلسلة القديمة لا تزال تُترجم دون تغيير (الآن مدعومة بالواجهات المرحلية القديمة):
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

نوع FluentConverter يعرض الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | تكوين المستند المصدر للتحويل. |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | تكوين مجموعة من المستندات المصدر. |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | تكوين تدفق المستند المصدر. |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | تكوين مجموعة من تدفقات المستندات المصدر. |
| [load_file](/conversion/python-net/groupdocs.conversion/fluentconverter/load_file/) |  |
| [load_files](/conversion/python-net/groupdocs.conversion/fluentconverter/load_files/) |  |
| [load_func](/conversion/python-net/groupdocs.conversion/fluentconverter/load_func/) |  |
| [load_string](/conversion/python-net/groupdocs.conversion/fluentconverter/load_string/) |  |
| [load_strings](/conversion/python-net/groupdocs.conversion/fluentconverter/load_strings/) |  |
| [with_events](/conversion/python-net/groupdocs.conversion/fluentconverter/with_events/#configure) | يبدأ سلسلة سلسة في مرحلة الدخول مع معالجات أحداث دورة حياة التحويل. |
| [with_settings](/conversion/python-net/groupdocs.conversion/fluentconverter/with_settings/#settings_provider) | تكوين إعدادات التحويل. |

### انظر أيضًا
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
