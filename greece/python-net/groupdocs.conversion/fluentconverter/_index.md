---
title: "Κλάση FluentConverter"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει μια ρευστή ρύθμιση μετατροπής."
type: docs
url: /el/python-net/groupdocs.conversion/fluentconverter/
is_root: false
weight: 120
---


## FluentConverter class

Αντιπροσωπεύει μια ρευστή ρύθμιση μετατροπής.

Δείγμα χρήσης ευέλικτης μετατροπής:

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// Συνιστάται: συγκεντρώστε τους διαχειριστές μέσω WithEvents στο αρχικό στάδιο (πριν το Load).
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
// Καθρέφτης ανά σελίδα: χειριστές ανά σελίδα μέσω WithEvents στο αρχικό στάδιο.
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
// Η κληρονομική αλυσίδα εξακολουθεί να μεταγλωττίζεται αμετάβλητη (τώρα υποστηρίζεται από τις παρωχημένες διεπαφές σταδίων):
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

Ο τύπος FluentConverter εκθέτει τα ακόλουθα μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | Διαμορφώστε το πηγαίο έγγραφο για μετατροπή. |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | Διαμορφώστε το σύνολο των πηγαίων εγγράφων. |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | Διαμορφώστε τη ροή του πηγαίου εγγράφου. |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | Διαμορφώστε ένα σύνολο ροών πηγαίων εγγράφων. |
| [load_file](/conversion/python-net/groupdocs.conversion/fluentconverter/load_file/) |  |
| [load_files](/conversion/python-net/groupdocs.conversion/fluentconverter/load_files/) |  |
| [load_func](/conversion/python-net/groupdocs.conversion/fluentconverter/load_func/) |  |
| [load_string](/conversion/python-net/groupdocs.conversion/fluentconverter/load_string/) |  |
| [load_strings](/conversion/python-net/groupdocs.conversion/fluentconverter/load_strings/) |  |
| [with_events](/conversion/python-net/groupdocs.conversion/fluentconverter/with_events/#configure) | Ξεκινά μια ευέλικτη αλυσίδα στο στάδιο εισόδου με χειριστές γεγονότων κύκλου ζωής της μετατροπής. |
| [with_settings](/conversion/python-net/groupdocs.conversion/fluentconverter/with_settings/#settings_provider) | Διαμορφώστε τις ρυθμίσεις μετατροπής. |

### Δείτε επίσης
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
