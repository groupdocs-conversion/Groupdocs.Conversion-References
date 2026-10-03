---
title: "NoteLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων One."
type: docs
weight: 2680
url: /el/net/groupdocs.conversion.options.load/noteloadoptions/
---
## NoteLoadOptions class

Επιλογές για τη φόρτωση εγγράφων One.

```csharp
public sealed class NoteLoadOptions : LoadOptions, IFontSubstituteLoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [NoteLoadOptions](noteloadoptions)() | Αρχικοποιεί νέο αντικείμενο της κλάσης [`NoteLoadOptions`](../noteloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/noteloadoptions/defaultfont) { get; set; } | Προεπιλεγμένη γραμματοσειρά για το έγγραφο Note. Η παρακάτω γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/noteloadoptions/fontsubstitutes) { get; set; } | Αντικαθιστά συγκεκριμένες γραμματοσειρές κατά τη μετατροπή του εγγράφου Note. |
| [Format](../../groupdocs.conversion.options.load/noteloadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. Είναι `null` μέχρι να οριστεί μια μορφή, έτσι ελέγξτε το για `null` αντί να το συγκρίνετε με [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), το οποίο ποτέ δεν ισούται. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| [Password](../../groupdocs.conversion.options.load/noteloadoptions/password) { get; set; } | Ορίστε κωδικό πρόσβασης για την αφαίρεση προστασίας του προστατευμένου εγγράφου. |

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
