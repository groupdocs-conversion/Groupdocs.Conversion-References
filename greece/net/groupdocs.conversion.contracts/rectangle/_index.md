---
title: "Ορθογώνιο"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Αναπαριστά ένα ορθογώνιο ορισμένο από τις άκρες του για σκοπούς περικοπής."
type: docs
weight: 580
url: /el/net/groupdocs.conversion.contracts/rectangle/
---
## Rectangle class

Αναπαριστά ένα ορθογώνιο ορισμένο από τις άκρες του για σκοπούς περικοπής.

```csharp
public sealed class Rectangle : ValueObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Rectangle](rectangle)(int, int, int, int) | Αρχικοποιεί μια νέα παρουσία της δομής [`Rectangle`](../rectangle) με καθορισμένες άκρες. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Bottom](../../groupdocs.conversion.contracts/rectangle/bottom) { get; } | Λαμβάνει την κάτω άκρη του ορθογωνίου. |
| [Height](../../groupdocs.conversion.contracts/rectangle/height) { get; } | Λαμβάνει το ύψος του ορθογωνίου βάσει των άνω και κάτω άκρων. |
| [Left](../../groupdocs.conversion.contracts/rectangle/left) { get; } | Λαμβάνει την αριστερή άκρη του ορθογωνίου. |
| [Right](../../groupdocs.conversion.contracts/rectangle/right) { get; } | Λαμβάνει τη δεξιά άκρη του ορθογωνίου. |
| [Top](../../groupdocs.conversion.contracts/rectangle/top) { get; } | Λαμβάνει την άνω άκρη του ορθογωνίου. |
| [Width](../../groupdocs.conversion.contracts/rectangle/width) { get; } | Λαμβάνει το πλάτος του ορθογωνίου βάσει των αριστερής και δεξιάς άκρων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Crop](../../groupdocs.conversion.contracts/rectangle/crop)(int, int, int, int) | Δημιουργεί μια περικομμένη έκδοση του τρέχοντος ορθογωνίου αφαιρώντας τις καθορισμένες περιθώριες. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |
| override [ToString](../../groupdocs.conversion.contracts/rectangle/tostring)() | Επιστρέφει μια αναπαράσταση σε συμβολοσειρά του ορθογωνίου. |

### Δείτε επίσης

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
