---
title: "Converter"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Rappresenta la classe principale che controlla il processo di conversione del documento."
type: docs
weight: 890
url: /it/net/groupdocs.conversion/converter/
---
## Converter class

Rappresenta la classe principale che controlla il processo di conversione del documento.

```csharp
public sealed class Converter : IDisposable
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | Inizializza una nuova istanza della classe [`Converter`](../converter). |
| [Converter](converter#constructor_5)(string) | Inizializza una nuova istanza della classe [`Converter`](../converter). |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Inizializza una nuova istanza della classe [`Converter`](../converter). |
| [Converter](converter#constructor_6)(string, Func&lt;ConverterSettings&gt;) | Inizializza una nuova istanza della classe [`Converter`](../converter). |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Inizializza una nuova istanza della classe [`Converter`](../converter) con eventi di conversione espliciti. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Inizializza una nuova istanza della classe [`Converter`](../converter). |
| [Converter](converter#constructor_7)(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Inizializza una nuova istanza della classe [`Converter`](../converter) con eventi di conversione espliciti. |
| [Converter](converter#constructor_8)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Inizializza una nuova istanza della classe [`Converter`](../converter). |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Inizializza una nuova istanza della classe [`Converter`](../converter) con eventi di conversione espliciti. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Inizializza una nuova istanza della classe [`Converter`](../converter) con eventi di conversione espliciti. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | Converte il documento di origine. Salva l'intero documento convertito. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Converte il documento di origine. Salva il documento convertito pagina per pagina. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | Converte il documento di origine. Salva l'intero documento convertito. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Converte il documento di origine. Salva il documento convertito pagina per pagina. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | Converte il documento di origine. Salva l'intero documento convertito. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Converte il documento di origine. Salva l'intero documento convertito. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | Converte il documento di origine. Salva il documento convertito pagina per pagina. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Converte il documento di origine. Salva il documento convertito pagina per pagina. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | Converte il documento di origine. Salva l'intero documento convertito. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Rilascia le risorse. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | Ottiene le informazioni del documento sorgente - conteggio delle pagine e altre proprietà del documento specifiche del tipo di file. |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | Ottiene le informazioni del documento sorgente - conteggio delle pagine e altre proprietà del documento specifiche del tipo di file. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Ottiene le conversioni possibili per il documento sorgente. |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | Verifica se il documento di origine è protetto da password |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Ottiene tutte le conversioni supportate |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Ottiene le conversioni supportate per l'estensione del documento fornita |

### Esempi

**Basic conversion from file path:**

```csharp
// Converti DOCX in PDF
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// Converti DOCX in PDF con filigrana e intervallo di pagine specifico
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
// Converti il documento da flusso a flusso
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
// Carica documento protetto da password e converti in PDF
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
// Converti le pagine del documento in file immagine separati
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
// Aggrega tutti i gestori di eventi in un contenitore ConversionEvents e passalo al Converter.
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

Le proprietà flat `OnConversionFailed`, `OnConversionByPageFailed` e `OnCompressionCompleted` su [`ConverterSettings`](../convertersettings) funzionano ancora ma sono obsolete; il nuovo codice dovrebbe passare un'istanza di [`ConversionEvents`](../conversionevents) tramite il parametro costruttore `events`.

**Get document information:**

```csharp
// Recupera i metadati del documento prima della conversione
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### IConversionConvertOptions

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
