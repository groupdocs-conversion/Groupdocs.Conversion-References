---
title: PdfOptimizationOptions
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Ορίζει επιλογές βελτιστοποίησης Pdf.
type: docs
weight: 1780
url: /el/net/groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
## PdfOptimizationOptions class

Ορίζει επιλογές βελτιστοποίησης Pdf.

```csharp
public sealed class PdfOptimizationOptions : ValueObject
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Αρχικοποιεί νέα παρουσία του[`PdfOptimizationOptions`](../pdfoptimizationoptions) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [CompressImages](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/compressimages) { get; set; } | Εάν το CompressImages έχει οριστεί σε`αληθής` , όλες οι εικόνες στο έγγραφο συμπιέζονται εκ νέου. Η συμπίεση ορίζεται από την ιδιότητα ImageQuality. |
| [ImageQuality](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/imagequality) { get; set; } | Τιμή σε ποσοστό όπου το 100% είναι αμετάβλητη ποιότητα και μέγεθος εικόνας. Για να μειώσετε το μέγεθος της εικόνας ορίστε αυτήν την ιδιότητα σε λιγότερο από 100 |
| [LinkDuplicateStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/linkduplicatestreams) { get; set; } | Σύνδεση διπλότυπων ροών |
| [RemoveUnusedObjects](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedobjects) { get; set; } | Αφαιρέστε αχρησιμοποίητα αντικείμενα |
| [RemoveUnusedStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedstreams) { get; set; } | Κατάργηση αχρησιμοποίητων ροών |
| [UnembedFonts](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/unembedfonts) { get; set; } | Κάντε τις γραμματοσειρές να μην είναι ενσωματωμένες εάν οριστεί σε true |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Εξυπηρετεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* χώρος ονομάτων [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* συνέλευση [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->