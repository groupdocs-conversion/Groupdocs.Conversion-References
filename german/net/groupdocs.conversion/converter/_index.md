---
title: "Converter"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Stellt die Hauptklasse dar, die den Dokumentkonvertierungsprozess steuert."
type: docs
weight: 890
url: /de/net/groupdocs.conversion/converter/
---
## Converter class

Stellt die Hauptklasse dar, die den Dokumentkonvertierungsprozess steuert.

```csharp
public sealed class Converter : IDisposable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | Initialisiert eine neue Instanz der [`Converter`](../converter)-Klasse. |
| [Converter](converter#constructor_5)(string) | Initialisiert eine neue Instanz der [`Converter`](../converter)-Klasse. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Initialisiert eine neue Instanz der [`Converter`](../converter)-Klasse. |
| [Converter](converter#constructor_6)(string, Func&lt;ConverterSettings&gt;) | Initialisiert eine neue Instanz der [`Converter`](../converter)-Klasse. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initialisiert eine neue Instanz der [`Converter`](../converter)-Klasse mit expliziten Konvertierungsereignissen. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialisiert eine neue Instanz der [`Converter`](../converter)-Klasse. |
| [Converter](converter#constructor_7)(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initialisiert eine neue Instanz der [`Converter`](../converter)-Klasse mit expliziten Konvertierungsereignissen. |
| [Converter](converter#constructor_8)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialisiert eine neue Instanz der [`Converter`](../converter)-Klasse. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initialisiert eine neue Instanz der [`Converter`](../converter)-Klasse mit expliziten Konvertierungsereignissen. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Initialisiert eine neue Instanz der [`Converter`](../converter)-Klasse mit expliziten Konvertierungsereignissen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Gibt Ressourcen frei. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | Liefert Informationen zum Quellendokument – Seitenanzahl und weitere dokumentenspezifische Eigenschaften des Dateityps. |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | Liefert Informationen zum Quellendokument – Seitenanzahl und weitere dokumentenspezifische Eigenschaften des Dateityps. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Liefert mögliche Konvertierungen für das Quellendokument. |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | Überprüft, ob das Quell‑Dokument passwortgeschützt ist |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Liefert alle unterstützten Konvertierungen |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Liefert unterstützte Konvertierungen für die angegebene Dokumenterweiterung |

### Beispiele

**Basic conversion from file path:**

```csharp
// DOCX in PDF konvertieren
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// DOCX in PDF mit Wasserzeichen und bestimmtem Seitenbereich konvertieren
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
// Dokument von Stream zu Stream konvertieren
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
// Passwortgeschütztes Dokument laden und in PDF konvertieren
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
// Dokumentseiten in separate Bilddateien konvertieren
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
// Alle Ereignis‑Handler in einem ConversionEvents‑Behälter aggregieren und an den Converter übergeben.
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

Die flachen `OnConversionFailed`, `OnConversionByPageFailed` und `OnCompressionCompleted` Eigenschaften auf [`ConverterSettings`](../convertersettings) funktionieren weiterhin, sind jedoch veraltet; neuer Code sollte eine [`ConversionEvents`](../conversionevents) Instanz über den `events` Konstruktorparameter übergeben.

**Get document information:**

```csharp
// Dokument‑Metadaten vor der Konvertierung abrufen
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### Siehe auch

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
