---
title: "Converter"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Stelt de hoofdklasse voor die het documentconversieproces beheert."
type: docs
weight: 890
url: /nl/net/groupdocs.conversion/converter/
---
## Converter class

Stelt de hoofdklasse voor die het documentconversieproces beheert.

```csharp
public sealed class Converter : IDisposable
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | Initialiseert een nieuw exemplaar van [`Converter`](../converter) klasse. |
| [Converter](converter#constructor_5)(string) | Initialiseert een nieuw exemplaar van [`Converter`](../converter) klasse. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Initialiseert een nieuw exemplaar van [`Converter`](../converter) klasse. |
| [Converter](converter#constructor_6)(string, Func&lt;ConverterSettings&gt;) | Initialiseert een nieuw exemplaar van [`Converter`](../converter) klasse. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initialiseert een nieuw exemplaar van [`Converter`](../converter) klasse met expliciete conversiegebeurtenissen. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialiseert een nieuw exemplaar van [`Converter`](../converter) klasse. |
| [Converter](converter#constructor_7)(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initialiseert een nieuw exemplaar van [`Converter`](../converter) klasse met expliciete conversiegebeurtenissen. |
| [Converter](converter#constructor_8)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialiseert een nieuw exemplaar van [`Converter`](../converter) klasse. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initialiseert een nieuw exemplaar van [`Converter`](../converter) klasse met expliciete conversiegebeurtenissen. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initialiseert een nieuw exemplaar van [`Converter`](../converter) klasse met expliciete conversiegebeurtenissen. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | Converteert brondocument. Slaat het volledige geconverteerde document op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | Converteert brondocument. Slaat het volledige geconverteerde document op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | Converteert brondocument. Slaat het volledige geconverteerde document op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Converteert brondocument. Slaat het volledige geconverteerde document op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | Converteert brondocument. Slaat het volledige geconverteerde document op. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Vrijgeeft bronnen |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | Haalt informatie over het bron‑document op – aantal pagina's en andere documenteigenschappen die specifiek zijn voor het bestandstype. |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | Haalt informatie over het bron‑document op – aantal pagina's en andere documenteigenschappen die specifiek zijn voor het bestandstype. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Haalt mogelijke conversies voor het bron‑document op. |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | Controleert of brondocument met wachtwoord is beveiligd |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Haalt alle ondersteunde conversies op |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Haalt ondersteunde conversies op voor opgegeven documentextensie |

### Voorbeelden

**Basic conversion from file path:**

```csharp
// Converteer DOCX naar PDF
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// Converteer DOCX naar PDF met watermerk en specifiek paginabereik
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
// Converteer document van stroom naar stroom
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
// Laad wachtwoordbeveiligd document en converteer naar PDF
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
// Converteer documentpagina's naar afzonderlijke afbeeldingsbestanden
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
// Aggregeer alle gebeurtenishandlers in een ConversionEvents-zak en geef deze door aan de Converter.
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

De platte `OnConversionFailed`, `OnConversionByPageFailed` en `OnCompressionCompleted` eigenschappen op [`ConverterSettings`](../convertersettings) werken nog, maar zijn verouderd; nieuwe code moet een [`ConversionEvents`](../conversionevents) instantie doorgeven via de `events` constructor‑parameter.

**Get document information:**

```csharp
// Haal documentmetadata op vóór conversie
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### Zie ook

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
