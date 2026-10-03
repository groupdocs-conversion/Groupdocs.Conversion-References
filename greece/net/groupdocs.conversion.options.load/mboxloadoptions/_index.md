---
title: "MboxLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων MBOX."
type: docs
weight: 2670
url: /el/net/groupdocs.conversion.options.load/mboxloadoptions/
---
## MboxLoadOptions class

Επιλογές για τη φόρτωση εγγράφων MBOX.

```csharp
public sealed class MboxLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MboxLoadOptions](mboxloadoptions)() | Αρχικοποιεί νέα παρουσία της κλάσης [`MboxLoadOptions`](../mboxloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/mboxloadoptions/convertowned) { get; } | Υλοποιεί [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) μόνο για ανάγνωση. Ορίζεται σε true. Τα ιδιοκτησιακά έγγραφα θα μετατραπούν. |
| [ConvertOwner](../../groupdocs.conversion.options.load/mboxloadoptions/convertowner) { get; } | Υλοποιεί [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) μόνο για ανάγνωση. Ορίζεται σε false. Ο κάτοχος δεν θα μετατραπεί. |
| [Depth](../../groupdocs.conversion.options.load/mboxloadoptions/depth) { get; set; } | Υλοποιεί [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Προεπιλογή: 3 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/mboxloadoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
