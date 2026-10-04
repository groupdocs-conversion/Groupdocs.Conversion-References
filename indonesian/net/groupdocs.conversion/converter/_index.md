---
title: "Converter"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mewakili kelas utama yang mengontrol proses konversi dokumen."
type: docs
weight: 890
url: /id/net/groupdocs.conversion/converter/
---
## Converter class

Mewakili kelas utama yang mengontrol proses konversi dokumen.

```csharp
public sealed class Converter : IDisposable
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | Menginisialisasi instance baru dari kelas [`Converter`](../converter). |
| [Converter](converter#constructor_5)(string) | Menginisialisasi instance baru dari kelas [`Converter`](../converter). |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Menginisialisasi instance baru dari kelas [`Converter`](../converter). |
| [Converter](converter#constructor_6)(string, Func&lt;ConverterSettings&gt;) | Menginisialisasi instance baru dari kelas [`Converter`](../converter). |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Menginisialisasi instance baru dari kelas [`Converter`](../converter) dengan peristiwa konversi eksplisit. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Menginisialisasi instance baru dari kelas [`Converter`](../converter). |
| [Converter](converter#constructor_7)(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Menginisialisasi instance baru dari kelas [`Converter`](../converter) dengan peristiwa konversi eksplisit. |
| [Converter](converter#constructor_8)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Menginisialisasi instance baru dari kelas [`Converter`](../converter). |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Menginisialisasi instance baru dari kelas [`Converter`](../converter) dengan peristiwa konversi eksplisit. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Menginisialisasi instance baru dari kelas [`Converter`](../converter) dengan peristiwa konversi eksplisit. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang telah dikonversi. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman per halaman. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang telah dikonversi. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman per halaman. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang telah dikonversi. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang telah dikonversi. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman per halaman. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman per halaman. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang telah dikonversi. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Melepaskan sumber daya. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | Mendapatkan info dokumen sumber - jumlah halaman dan properti dokumen lain yang spesifik untuk tipe file. |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | Mendapatkan info dokumen sumber - jumlah halaman dan properti dokumen lain yang spesifik untuk tipe file. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Mendapatkan konversi yang memungkinkan untuk dokumen sumber. |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | Memeriksa apakah dokumen sumber dilindungi kata sandi |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Mendapatkan semua konversi yang didukung |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Mendapatkan konversi yang didukung untuk ekstensi dokumen yang diberikan |

### Contoh

**Basic conversion from file path:**

```csharp
// Konversi DOCX ke PDF
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// Konversi DOCX ke PDF dengan watermark dan rentang halaman tertentu
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
// Konversi dokumen dari stream ke stream
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
// Muat dokumen yang dilindungi kata sandi dan konversi ke PDF
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
// Konversi halaman dokumen ke file gambar terpisah
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
// Kumpulkan semua penangan peristiwa dalam sebuah wadah ConversionEvents dan berikan ke Converter.
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

Properti datar `OnConversionFailed`, `OnConversionByPageFailed`, dan `OnCompressionCompleted` pada [`ConverterSettings`](../convertersettings) masih berfungsi tetapi sudah usang; kode baru harus mengirimkan sebuah instance [`ConversionEvents`](../conversionevents) melalui parameter konstruktor `events`.

**Get document information:**

```csharp
// Mengambil metadata dokumen sebelum konversi
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### Lihat Juga

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
