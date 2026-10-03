---
title: "PossibleConversions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Αναπαριστά μια αντιστοίχηση των ζευγών μετατροπής που υποστηρίζονται για συγκεκριμένη μορφή αρχείου προέλευσης"
type: docs
weight: 510
url: /el/net/groupdocs.conversion.contracts/possibleconversions/
---
## PossibleConversions class

Αναπαριστά μια αντιστοίχηση των ζευγών μετατροπής που υποστηρίζονται για συγκεκριμένη μορφή αρχείου προέλευσης

```csharp
public sealed class PossibleConversions : ValueObject
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [All](../../groupdocs.conversion.contracts/possibleconversions/all) { get; } | Όλοι οι τύποι αρχείων προορισμού και η σημαία πρωτεύον/δευτερεύον IEnumerable του [`TargetConversion`](../targetconversion) |
| [Item](../../groupdocs.conversion.contracts/possibleconversions/item) { get; } | Επιστρέφει τη μετατροπή προορισμού για τον καθορισμένο τύπο αρχείου προορισμού (2 δείκτες) |
| [LoadOptions](../../groupdocs.conversion.contracts/possibleconversions/loadoptions) { get; } | Προκαθορισμένες επιλογές φόρτωσης που μπορούν να χρησιμοποιηθούν για μετατροπή από τον τρέχον τύπο |
| [Primary](../../groupdocs.conversion.contracts/possibleconversions/primary) { get; } | Πρωτεύοντες τύποι αρχείων προορισμού |
| [Secondary](../../groupdocs.conversion.contracts/possibleconversions/secondary) { get; } | Δευτερεύοντες τύποι αρχείων προορισμού |
| [Source](../../groupdocs.conversion.contracts/possibleconversions/source) { get; } | Μορφές αρχείων προέλευσης |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
