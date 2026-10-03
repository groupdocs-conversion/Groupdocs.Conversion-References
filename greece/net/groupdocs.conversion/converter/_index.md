---
title: "Converter"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Αναπαριστά την κύρια κλάση που ελέγχει τη διαδικασία μετατροπής εγγράφων."
type: docs
weight: 890
url: /el/net/groupdocs.conversion/converter/
---
## Converter class

Αναπαριστά την κύρια κλάση που ελέγχει τη διαδικασία μετατροπής εγγράφων.

```csharp
public sealed class Converter : IDisposable
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Converter](converter#constructor)(Func&lt;Stream&gt;) | Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../converter). |
| [Converter](converter#constructor_5)(string) | Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../converter). |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../converter). |
| [Converter](converter#constructor_6)(string, Func&lt;ConverterSettings&gt;) | Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../converter). |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../converter) με ρητά συμβάντα μετατροπής. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../converter). |
| [Converter](converter#constructor_7)(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../converter) με ρητά συμβάντα μετατροπής. |
| [Converter](converter#constructor_8)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../converter). |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../converter) με ρητά συμβάντα μετατροπής. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) | Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../converter) με ρητά συμβάντα μετατροπής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) | Μετατρέπει το έγγραφο πηγής. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Μετατρέπει το έγγραφο πηγής. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) | Μετατρέπει το έγγραφο πηγής. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) | Μετατρέπει το έγγραφο πηγής. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) | Μετατρέπει το έγγραφο πηγής. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Μετατρέπει το έγγραφο πηγής. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) | Μετατρέπει το έγγραφο πηγής. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) | Μετατρέπει το έγγραφο πηγής. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(string, ConvertOptions, CancellationToken) | Μετατρέπει το έγγραφο πηγής. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Απελευθερώνει πόρους. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo)() | Λαμβάνει πληροφορίες του πηγαίου εγγράφου - αριθμός σελίδων και άλλες ιδιότητες εγγράφου ειδικές για τον τύπο αρχείου. |
| [GetDocumentInfo&lt;T&gt;](../../groupdocs.conversion/converter/getdocumentinfo#getdocumentinfo_1)() | Λαμβάνει πληροφορίες του πηγαίου εγγράφου - αριθμός σελίδων και άλλες ιδιότητες εγγράφου ειδικές για τον τύπο αρχείου. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Λαμβάνει τις πιθανές μετατροπές για το πηγαίο έγγραφο. |
| [IsDocumentPasswordProtected](../../groupdocs.conversion/converter/isdocumentpasswordprotected)() | Ελέγχει αν το έγγραφο πηγής είναι προστατευμένο με κωδικό. |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Λαμβάνει όλες τις υποστηριζόμενες μετατροπές. |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Λαμβάνει τις υποστηριζόμενες μετατροπές για την παρεχόμενη επέκταση εγγράφου. |

### Παραδείγματα

**Basic conversion from file path:**

```csharp
// Μετατροπή DOCX σε PDF
using (var converter = new Converter("sample.docx"))
{
    var options = new PdfConvertOptions();
    converter.Convert("output.pdf", options);
}
```

**Conversion with custom options:**

```csharp
// Μετατροπή DOCX σε PDF με υδατογράφημα και συγκεκριμένο εύρος σελίδων
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
// Μετατροπή εγγράφου από ροή σε ροή
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
// Φόρτωση εγγράφου με προστασία κωδικού και μετατροπή σε PDF
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
// Μετατροπή σελίδων εγγράφου σε ξεχωριστά αρχεία εικόνας
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
// Συγκεντρώστε όλους τους διαχειριστές συμβάντων σε μια συλλογή ConversionEvents και περάστε την στον Converter.
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

Οι επίπεδες ιδιότητες `OnConversionFailed`, `OnConversionByPageFailed` και `OnCompressionCompleted` στην κλάση [`ConverterSettings`](../convertersettings) λειτουργούν ακόμη αλλά είναι παρωχημένες· ο νέος κώδικας πρέπει να περάσει μια παρουσία [`ConversionEvents`](../conversionevents) μέσω της παραμέτρου κατασκευής `events`.

**Get document information:**

```csharp
// Ανακτήστε τα μεταδεδομένα του εγγράφου πριν από τη μετατροπή
using (var converter = new Converter("sample.docx"))
{
    var info = converter.GetDocumentInfo();
    Console.WriteLine($"Document has {info.PagesCount} pages");
    Console.WriteLine($"Format: {info.Format}");
    Console.WriteLine($"Size: {info.Size} bytes");
}
```

### Δείτε επίσης

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
