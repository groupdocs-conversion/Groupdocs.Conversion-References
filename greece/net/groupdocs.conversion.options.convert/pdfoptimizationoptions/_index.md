---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει τις επιλογές βελτιστοποίησης Pdf."
type: docs
weight: 2120
url: /el/net/groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
## PdfOptimizationOptions class

Ορίζει τις επιλογές βελτιστοποίησης Pdf.

```csharp
public sealed class PdfOptimizationOptions : ValueObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Αρχικοποιεί νέα παρουσία της κλάσης [`PdfOptimizationOptions`](../pdfoptimizationoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CompressImages](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/compressimages) { get; set; } | Εάν το CompressImages οριστεί σε `true`, όλες οι εικόνες στο έγγραφο θα επανασυμπιεστούν. Η συμπίεση ορίζεται από την ιδιότητα ImageQuality. |
| [FontSubsetStrategy](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/fontsubsetstrategy) { get; set; } | Ορίστε τη στρατηγική υποσυνόλου γραμματοσειράς |
| [ImageQuality](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/imagequality) { get; set; } | Τιμή σε ποσοστό όπου το 100% αντιστοιχεί στην αμετάβλητη ποιότητα και μέγεθος εικόνας. Για να μειώσετε το μέγεθος της εικόνας, ορίστε αυτή την ιδιότητα σε λιγότερο από 100 |
| [LinkDuplicateStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/linkduplicatestreams) { get; set; } | Σύνδεση διπλών ροών |
| [RemoveUnusedObjects](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedobjects) { get; set; } | Αφαίρεση αχρησιμοποίητων αντικειμένων |
| [RemoveUnusedStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedstreams) { get; set; } | Αφαίρεση αχρησιμοποίητων ροών |
| [UnembedFonts](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/unembedfonts) { get; set; } | Μην ενσωματώνετε γραμματοσειρές εάν οριστεί σε true |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
