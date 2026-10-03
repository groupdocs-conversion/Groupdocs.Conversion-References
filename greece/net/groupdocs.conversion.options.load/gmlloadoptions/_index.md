---
title: "GmlLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων GML."
type: docs
weight: 2550
url: /el/net/groupdocs.conversion.options.load/gmlloadoptions/
---
## GmlLoadOptions class

Επιλογές για τη φόρτωση εγγράφων GML.

```csharp
public sealed class GmlLoadOptions : GisLoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [GmlLoadOptions](gmlloadoptions)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [`GmlLoadOptions`](../gmlloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gmlloadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | Ορίζει το επιθυμητό ύψος σελίδας για τη μετατροπή του εγγράφου GIS. Η προεπιλογή είναι 1000. |
| [LoadSchemasFromInternet](../../groupdocs.conversion.options.load/gmlloadoptions/loadschemasfrominternet) { get; set; } | Καθορίζει εάν η Conversion επιτρέπεται να φορτώσει σχήμα XML από το Διαδίκτυο. Εάν οριστεί σε false, τα σχήματα με απόλυτες URI που δεν ξεκινούν με ‘file://’ δεν θα φορτωθούν. Η προεπιλογή είναι false. |
| [RestoreSchema](../../groupdocs.conversion.options.load/gmlloadoptions/restoreschema) { get; set; } | Καθορίζει εάν η Conversion επιτρέπεται να αναλύσει τα χαρακτηριστικά σε ένα αρχείο Gml στο οποίο λείπει ή δεν μπορεί να φορτωθεί σχήμα XML. Εάν οριστεί σε true, ο αναγνώστης Conversion δεν απαιτεί την παρουσία σχήματος XML. Η προεπιλογή είναι false. |
| [SchemaLocation](../../groupdocs.conversion.options.load/gmlloadoptions/schemalocation) { get; set; } | Λίστα ζευγών URI χωρισμένων με κενό. Το πρώτο URI σε κάθε ζεύγος είναι το URI του χώρου ονομάτων, το δεύτερο URI είναι η Διαδρομή προς το σχήμα XML του χώρου ονομάτων. Εάν οριστεί σε null, η Conversion θα προσπαθήσει να διαβάσει το schemaLocation από το στοιχείο ρίζας του εγγράφου. Η προεπιλογή είναι null |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | Ορίζει το επιθυμητό πλάτος σελίδας για τη μετατροπή του εγγράφου GIS. Η προεπιλογή είναι 1000. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [GisLoadOptions](../gisloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
