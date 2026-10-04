---
title: "Converter"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "Belge dönüştürme sürecini kontrol eden ana sınıfı temsil eder."
type: docs
weight: 890
url: /tr/net/groupdocs.conversion/converter/
---
## Converter class

Belge dönüştürme sürecini kontrol eden ana sınıfı temsil eder.

```csharp
public sealed class Converter : IDisposable
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | Yeni bir [`Converter`](../converter) sınıfının örneğini başlatır. |
| [Converter](converter#constructor_5)(string) | Yeni bir [`Converter`](../converter) sınıfının örneğini başlatır. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Yeni bir [`Converter`](../converter) sınıfının örneğini başlatır. |
| [Converter](converter#constructor_6)(string, Func&lt;ConverterSettings&gt;) | Yeni bir [`Converter`](../converter) sınıfının örneğini başlatır. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Açık dönüşüm olaylarıyla yeni bir [`Converter`](../converter) sınıfının örneğini başlatır. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Yeni bir [`Converter`](../converter) sınıfının örneğini başlatır. |
| [Converter](converter#constructor_7)(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Açık dönüşüm olaylarıyla yeni bir [`Converter`](../converter) sınıfının örneğini başlatır. |
| [Converter](converter#constructor_8)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Yeni bir [`Converter`](../converter) sınıfının örneğini başlatır. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Açık dönüşüm olaylarıyla yeni bir [`Converter`](../converter) sınıfının örneğini başlatır. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Açık dönüşüm olaylarıyla yeni bir [`Converter`](../converter) sınıfının örneğini başlatır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | Kaynak belgeyi dönüştürür. Dönüştürülmüş belgenin tamamını kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | Kaynak belgeyi dönüştürür. Dönüştürülmüş belgenin tamamını kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | Kaynak belgeyi dönüştürür. Dönüştürülmüş belgenin tamamını kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Kaynak belgeyi dönüştürür. Dönüştürülmüş belgenin tamamını kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | Kaynak belgeyi dönüştürür. Dönüştürülmüş belgenin tamamını kaydeder. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Kaynakları serbest bırakır. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | Kaynak belge bilgilerini alır - sayfa sayısı ve dosya türüne özgü diğer belge özellikleri. |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | Kaynak belge bilgilerini alır - sayfa sayısı ve dosya türüne özgü diğer belge özellikleri. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Kaynak belge için olası dönüşümleri alır. |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | Kaynak belgenin şifre korumalı olup olmadığını kontrol eder. |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Desteklenen tüm dönüşümleri alır. |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Sağlanan belge uzantısı için desteklenen dönüşümleri alır. |

### Örnekler

**Basic conversion from file path:**

```csharp
// DOCX'i PDF'e dönüştür
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// DOCX'i filigran ve belirli sayfa aralığıyla PDF'e dönüştür
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
// Belgeyi akıştan akışa dönüştür
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
// Şifre korumalı belgeyi yükle ve PDF'e dönüştür
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
// Belge sayfalarını ayrı görüntü dosyalarına dönüştür
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
// Tüm olay işleyicilerini bir ConversionEvents çantasında toplayın ve Converter'a iletin.
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

Düz `OnConversionFailed`, `OnConversionByPageFailed` ve `OnCompressionCompleted` özellikleri [`ConverterSettings`](../convertersettings) üzerinde hâlâ çalışır ancak artık kullanımdan kaldırılmıştır; yeni kod bir [`ConversionEvents`](../conversionevents) örneğini `events` yapıcı parametresi aracılığıyla geçirmelidir.

**Get document information:**

```csharp
// Dönüşümden önce belge meta verilerini al.
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### Ayrıca Bakınız

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
