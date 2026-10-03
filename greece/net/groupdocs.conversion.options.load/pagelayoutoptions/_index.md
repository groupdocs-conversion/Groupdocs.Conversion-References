---
title: "PageLayoutOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Περιγράφει τις λειτουργίες διάταξης σελίδας κατά τη φόρτωση εγγράφων web."
type: docs
weight: 2720
url: /el/net/groupdocs.conversion.options.load/pagelayoutoptions/
---
## PageLayoutOptions class

Περιγράφει τις λειτουργίες διάταξης σελίδας κατά τη φόρτωση εγγράφων web.

```csharp
public class PageLayoutOptions : FlagsEnumeration
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Συγκρίνει το τρέχον αντικείμενο με άλλο. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |
| virtual [HasFlag&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/hasflag)(T) | Ελέγχει εάν η τρέχουσα σημαία έχει τη συγκεκριμένη σημαία. |
| virtual [HasFlagValue](../../groupdocs.conversion.contracts/flagsenumeration/hasflagvalue)(int) | Ελέγχει εάν η τρέχουσα σημαία έχει τη συγκεκριμένη τιμή. |
| override [ToString](../../groupdocs.conversion.contracts/flagsenumeration/tostring)() | Μετατρέπει το τρέχον αντικείμενο σε συμβολοσειρά. |
| [operator &#x7C;](../../groupdocs.conversion.options.load/pagelayoutoptions/op_bitwiseor) | Συνδυάζει δύο σημαίες [`PageLayoutOptions`](../pagelayoutoptions) χρησιμοποιώντας το λογικό OR. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| static readonly [None](../../groupdocs.conversion.options.load/pagelayoutoptions/none) | Προεπιλεγμένη τιμή |
| static readonly [ScaleToPageHeight](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopageheight) | Αυτή η σημαία υποδεικνύει ότι το περιεχόμενο του εγγράφου θα κλιμακωθεί ώστε να ταιριάζει στο ύψος της πρώτης σελίδας. Όλο το περιεχόμενο του εγγράφου θα τοποθετηθεί μόνο στην ενιαία σελίδα. |
| static readonly [ScaleToPageWidth](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopagewidth) | Υποδεικνύει ότι το περιεχόμενο του εγγράφου θα κλιμακωθεί ώστε να ταιριάζει στη σελίδα όπου η διαφορά μεταξύ του διαθέσιμου πλάτους σελίδας και του επικαλυπτόμενου περιεχομένου είναι η μεγαλύτερη. |

### Δείτε επίσης

* class [FlagsEnumeration](../../groupdocs.conversion.contracts/flagsenumeration)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
