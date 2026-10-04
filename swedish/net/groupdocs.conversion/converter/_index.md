---
title: "Converter"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Representerar huvudklassen som styr dokumentkonverteringsprocessen."
type: docs
weight: 890
url: /sv/net/groupdocs.conversion/converter/
---
## Converter class

Representerar huvudklassen som styr dokumentkonverteringsprocessen.

```csharp
public sealed class Converter : IDisposable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | Initierar en ny instans av [`Converter`](../converter) klass. |
| [Converter](converter#constructor_5)(string) | Initierar en ny instans av [`Converter`](../converter) klass. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Initierar en ny instans av [`Converter`](../converter) klass. |
| [Converter](converter#constructor_6)(string, Func&lt;ConverterSettings&gt;) | Initierar en ny instans av [`Converter`](../converter) klass. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initierar en ny instans av [`Converter`](../converter) klass med explicita konverteringshändelser. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initierar en ny instans av [`Converter`](../converter) klass. |
| [Converter](converter#constructor_7)(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initierar en ny instans av [`Converter`](../converter) klass med explicita konverteringshändelser. |
| [Converter](converter#constructor_8)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initierar en ny instans av [`Converter`](../converter) klass. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initierar en ny instans av [`Converter`](../converter) klass med explicita konverteringshändelser. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initierar en ny instans av [`Converter`](../converter) klass med explicita konverteringshändelser. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | Konverterar källdokumentet. Sparar hela det konverterade dokumentet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | Konverterar källdokumentet. Sparar hela det konverterade dokumentet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | Konverterar källdokumentet. Sparar hela det konverterade dokumentet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Konverterar källdokumentet. Sparar hela det konverterade dokumentet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | Konverterar källdokumentet. Sparar hela det konverterade dokumentet. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Frigör resurser. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | Hämtar information om källdokumentet – sidantal och andra dokumentegenskaper specifika för filtypen. |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | Hämtar information om källdokumentet – sidantal och andra dokumentegenskaper specifika för filtypen. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Hämtar möjliga konverteringar för källdokumentet. |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | Kontrollerar om källdokumentet är lösenordsskyddat |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Hämtar alla stödjade konverteringar |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Hämtar stödjade konverteringar för angiven dokumentändelse |

### Exempel

**Basic conversion from file path:**

```csharp
// Konvertera DOCX till PDF
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// Konvertera DOCX till PDF med vattenstämpel och specifikt sidintervall
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
// Konvertera dokument från ström till ström
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
// Läs in lösenordsskyddat dokument och konvertera till PDF
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
// Konvertera dokumentsidor till separata bildfiler
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
// Samla alla händelsehanterare i en ConversionEvents‑påse och skicka den till Converter.
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

Den platta `OnConversionFailed`, `OnConversionByPageFailed` och `OnCompressionCompleted`‑egenskaperna på [`ConverterSettings`](../convertersettings) fungerar fortfarande men är föråldrade; ny kod bör skicka en [`ConversionEvents`](../conversionevents)‑instans via `events`‑konstruktörsparametern.

**Get document information:**

```csharp
// Hämta dokumentmetadata före konvertering
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### Se även

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
