---
title: "FluentConverter"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Κλάση για ρύθμιση fluent μετατροπής."
type: docs
weight: 1580
url: /el/net/groupdocs.conversion/fluentconverter/
---
## FluentConverter class

Κλάση για ρύθμιση fluent μετατροπής.

```csharp
public static class FluentConverter
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_1)(Func&lt;Stream&gt;) | Διαμορφώστε τη ροή του πηγαίου εγγράφου |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load)(Func&lt;Stream[]&gt;) | Διαμορφώστε το σύνολο των ροών των πηγαίων εγγράφων |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_2)(string) | Διαμορφώστε το πηγαίο έγγραφο για μετατροπή |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_3)(string[]) | Διαμορφώστε το σύνολο των πηγαίων εγγράφων |
| static [WithEvents](../../groupdocs.conversion/fluentconverter/withevents)(Action&lt;ConversionEvents&gt;) | Παραλλαγή του αρχικού σταδίου της αλυσίδας fluent που ξεκινά με χειριστές γεγονότων κύκλου ζωής μετατροπής. Καταλαμβάνει το ίδιο αρχικό στάδιο με [`WithSettings`](./withsettings), και η προκύπτουσα τσάντα [`ConversionEvents`](../conversionevents) ενεργοποιείται σε κάθε εκτέλεση μετατροπής από τον μετατροπέα. |
| static [WithSettings](../../groupdocs.conversion/fluentconverter/withsettings)(Func&lt;ConverterSettings&gt;) | Διαμορφώστε τις ρυθμίσεις μετατροπής |

### Παρατηρήσεις

Παράδειγμα χρήσης fluent μετατροπής:

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// Συνιστάται: συγκεντρώστε τους χειριστές μέσω WithEvents στο αρχικό στάδιο (πριν το Load).
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
// Καθρεφτισμός ανά σελίδα: χειριστές ανά σελίδα μέσω WithEvents στο αρχικό στάδιο.
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

### Δείτε επίσης

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
