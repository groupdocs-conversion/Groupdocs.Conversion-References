---
title: "FluentConverter"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Kelas untuk pengaturan konversi secara fluent."
type: docs
weight: 1580
url: /id/net/groupdocs.conversion/fluentconverter/
---
## FluentConverter class

Kelas untuk pengaturan konversi secara fluent.

```csharp
public static class FluentConverter
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_1)(Func&lt;Stream&gt;) | Konfigurasikan aliran dokumen sumber |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load)(Func&lt;Stream[]&gt;) | Konfigurasikan kumpulan aliran dokumen sumber |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_2)(string) | Konfigurasikan dokumen sumber untuk konversi |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_3)(string[]) | Konfigurasikan kumpulan dokumen sumber |
| static [WithEvents](../../groupdocs.conversion/fluentconverter/withevents)(Action&lt;ConversionEvents&gt;) | Varian tahap masuk dari rantai fluent yang dimulai dengan penangan peristiwa siklus hidup konversi. Berada pada tahap masuk yang sama dengan [`WithSettings`](./withsettings), dan kantong [`ConversionEvents`](../conversionevents) yang dihasilkan dipicu pada setiap proses konversi oleh konverter. |
| static [WithSettings](../../groupdocs.conversion/fluentconverter/withsettings)(Func&lt;ConverterSettings&gt;) | Konfigurasikan pengaturan konversi |

### Catatan

Contoh penggunaan konversi fluent:

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// Disarankan: gabungkan penangan melalui WithEvents pada tahap awal (sebelum Load).
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
// Cermin per halaman: penangan per halaman melalui WithEvents pada tahap awal.
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
// Rantai legacy masih dapat dikompilasi tanpa perubahan (sekarang didukung oleh antarmuka staged yang usang):
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

### Lihat Juga

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
