---
title: "PageSizeOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Αντιπροσωπεύει τις επιλογές που υποστηρίζουν το μέγεθος σελίδας."
type: docs
weight: 2990
url: /el/net/groupdocs.conversion.options/pagesizeoptions/
---
## PageSizeOptions class

Αντιπροσωπεύει τις επιλογές που υποστηρίζουν το μέγεθος σελίδας.

```csharp
public sealed class PageSizeOptions : ValueObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PageSizeOptions](pagesizeoptions)() | Προεπιλεγμένος κατασκευαστής. Αρχικοποιεί το [`PageSize`](./pagesize) σε [`Unset`](../pagesize/unset). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [PageHeight](../../groupdocs.conversion.options/pagesizeoptions/pageheight) { get; set; } | Ύψος σελίδας σε σημεία που θα εφαρμοστεί πριν τη μετατροπή. Όταν οριστεί, το [`PageSize`](./pagesize) αλλάζει αυτόματα σε [`Custom`](../pagesize/custom). |
| [PageSize](../../groupdocs.conversion.options/pagesizeoptions/pagesize) { get; set; } | Υλοποιεί [`PageSize`](../pagesize) |
| [PageWidth](../../groupdocs.conversion.options/pagesizeoptions/pagewidth) { get; set; } | Πλάτος σελίδας σε μονάδες point που θα εφαρμοστεί πριν από τη μετατροπή. Όταν οριστεί, το [`PageSize`](./pagesize) αλλάζει αυτόματα σε [`Custom`](../pagesize/custom). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options](../../groupdocs.conversion.options)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
