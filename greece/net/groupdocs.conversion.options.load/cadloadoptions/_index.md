---
title: "CadLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων CAD."
type: docs
weight: 2430
url: /el/net/groupdocs.conversion.options.load/cadloadoptions/
---
## CadLoadOptions class

Επιλογές για τη φόρτωση εγγράφων CAD.

```csharp
public sealed class CadLoadOptions : LoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [CadLoadOptions](cadloadoptions)() | Αρχικοποιεί νέα παρουσία της κλάσης [`CadLoadOptions`](../cadloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/cadloadoptions/backgroundcolor) { get; set; } | Λαμβάνει ή ορίζει ένα χρώμα φόντου. |
| [CtbSources](../../groupdocs.conversion.options.load/cadloadoptions/ctbsources) { get; set; } | Λαμβάνει ή ορίζει τις πηγές CTB. |
| [DrawColor](../../groupdocs.conversion.options.load/cadloadoptions/drawcolor) { get; set; } | Λαμβάνει ή ορίζει το χρώμα προσκηνίου. |
| [DrawType](../../groupdocs.conversion.options.load/cadloadoptions/drawtype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο σχεδίασης. |
| [Format](../../groupdocs.conversion.options.load/cadloadoptions/format) { get; set; } | Τύπος αρχείου εισαγόμενου εγγράφου. Είναι `null` μέχρι να οριστεί μια μορφή, έτσι ελέγξτε το για `null` αντί να το συγκρίνετε με [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), το οποίο ποτέ δεν ισούται. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| [LayoutNames](../../groupdocs.conversion.options.load/cadloadoptions/layoutnames) { get; set; } | Καθορίζει ποια διατάξεις CAD θα μετατραπούν |
| [LayoutScope](../../groupdocs.conversion.options.load/cadloadoptions/layoutscope) { get; set; } | Λαμβάνει ή ορίζει ποιοι χώροι σχεδίασης θα μετατραπούν. Η προεπιλογή είναι [`Both`](../cadlayoutscope/both), η οποία δεν περιορίζει τη μετατροπή. Αγνοείται όταν παρέχεται το [`LayoutNames`](./layoutnames), επειδή τα ρητά ονόματα διατάξεων έχουν προτεραιότητα. Μια τιμή `null` αντιμετωπίζεται ως [`Both`](../cadlayoutscope/both). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
