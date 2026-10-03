---
title: "CompressionLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων συμπίεσης."
type: docs
weight: 2440
url: /el/net/groupdocs.conversion.options.load/compressionloadoptions/
---
## CompressionLoadOptions class

Επιλογές για τη φόρτωση εγγράφων συμπίεσης.

```csharp
public sealed class CompressionLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [CompressionLoadOptions](compressionloadoptions)() | Αρχικοποιεί νέο αντικείμενο της κλάσης [`CompressionLoadOptions`](../compressionloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/compressionloadoptions/convertowned) { get; } | Υλοποιεί [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) μόνο για ανάγνωση. Ορίζεται σε true. Τα ιδιοκτησιακά έγγραφα θα μετατραπούν. |
| [ConvertOwner](../../groupdocs.conversion.options.load/compressionloadoptions/convertowner) { get; } | Υλοποιεί [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) μόνο για ανάγνωση. Ορίζεται σε false. Ο κάτοχος δεν θα μετατραπεί. |
| [Depth](../../groupdocs.conversion.options.load/compressionloadoptions/depth) { get; set; } | Υλοποιεί [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Προεπιλογή: 3 |
| [Format](../../groupdocs.conversion.options.load/compressionloadoptions/format) { get; set; } | Τύπος αρχείου εισαγόμενου εγγράφου. Είναι `null` μέχρι να οριστεί μια μορφή, έτσι ελέγξτε το για `null` αντί να το συγκρίνετε με [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), το οποίο ποτέ δεν ισούται. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| [Password](../../groupdocs.conversion.options.load/compressionloadoptions/password) { get; set; } | Ορίστε κωδικό πρόσβασης για τη φόρτωση προστατευμένου εγγράφου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
