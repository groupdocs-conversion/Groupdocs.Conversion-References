---
title: "PublisherLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων Publisher."
type: docs
weight: 2790
url: /el/net/groupdocs.conversion.options.load/publisherloadoptions/
---
## PublisherLoadOptions class

Επιλογές για τη φόρτωση εγγράφων Publisher.

```csharp
public class PublisherLoadOptions : LoadOptions, IFontSubstituteLoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PublisherLoadOptions](publisherloadoptions)() | Αρχικοποιεί νέα παρουσία της κλάσης [`PublisherLoadOptions`](../publisherloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/publisherloadoptions/defaultfont) { get; set; } | Προεπιλεγμένη γραμματοσειρά για έγγραφο Publisher. Η παρακάτω γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/publisherloadoptions/fontsubstitutes) { get; set; } | Αντικαταστήστε συγκεκριμένες γραμματοσειρές κατά τη μετατροπή εγγράφου Publisher. |
| [Format](../../groupdocs.conversion.options.load/publisherloadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. Είναι `null` μέχρι να οριστεί μια μορφή, έτσι ελέγξτε το για `null` αντί να το συγκρίνετε με [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), το οποίο ποτέ δεν ισούται. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [LoadOptions](../loadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
