---
title: "NsfLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων NSF."
type: docs
weight: 2690
url: /el/net/groupdocs.conversion.options.load/nsfloadoptions/
---
## NsfLoadOptions class

Επιλογές για τη φόρτωση εγγράφων NSF.

```csharp
public sealed class NsfLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [NsfLoadOptions](nsfloadoptions)() | Αρχικοποιεί νέα παρουσία της κλάσης [`NsfLoadOptions`](../nsfloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/nsfloadoptions/convertowned) { get; } | Υλοποιεί [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) μόνο για ανάγνωση. Ορίζεται σε true. Τα ιδιοκτησιακά έγγραφα θα μετατραπούν. |
| [ConvertOwner](../../groupdocs.conversion.options.load/nsfloadoptions/convertowner) { get; } | Υλοποιεί [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) μόνο για ανάγνωση. Ορίζεται σε false. Ο κάτοχος δεν θα μετατραπεί. |
| [Depth](../../groupdocs.conversion.options.load/nsfloadoptions/depth) { get; set; } | Υλοποιεί [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Προεπιλογή: 3 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/nsfloadoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
