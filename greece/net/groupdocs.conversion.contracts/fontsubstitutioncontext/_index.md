---
title: "FontSubstitutionContext"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Περιγράφει μια μοναδική αντικατάσταση γραμματοσειράς που συνέβη κατά τη φόρτωση ή την απόδοση ενός εγγράφου προέλευσης. Τα στιγμιότυπα περνούν στο OnFontSubstituted../groupdocs.conversion/conversionevents/onfontsubstituted."
type: docs
weight: 250
url: /el/net/groupdocs.conversion.contracts/fontsubstitutioncontext/
---
## FontSubstitutionContext class

Περιγράφει μια μοναδική αντικατάσταση γραμματοσειράς που συνέβη κατά τη φόρτωση ή την απόδοση ενός εγγράφου προέλευσης. Τα στιγμιότυπα περνούν στο [`OnFontSubstituted`](../../groupdocs.conversion/conversionevents/onfontsubstituted).

```csharp
public sealed class FontSubstitutionContext
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [FontSubstitutionContext](fontsubstitutioncontext)(string, string, string, string) | Δημιουργεί ένα νέο [`FontSubstitutionContext`](../fontsubstitutioncontext). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [OriginalFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/originalfontname) { get; } | Όνομα της γραμματοσειράς που αναφέρεται από το έγγραφο προέλευσης αλλά δεν είναι διαθέσιμη στην αλυσίδα μετατροπής. |
| [Reason](../../groupdocs.conversion.contracts/fontsubstitutioncontext/reason) { get; } | Το μήνυμα αντικατάστασης ακριβώς όπως αναφέρεται από τη γραμμή μετατροπής, κυριολεκτικά και αδιάσπαστο. Για έγγραφα που εκθέτουν τα ονόματα γραμματοσειρών δομημένα αυτό μπορεί να είναι `null` (χρησιμοποιήστε [`OriginalFontName`](./originalfontname) / [`SubstituteFontName`](./substitutefontname)); για άλλα μεταφέρει την πλήρη περιγραφή που είναι αναγνώσιμη από άνθρωπο, η οποία ονομάζει τόσο τη χαμένη όσο και τη γραμματοσειρά αντικατάστασης. |
| [SourceFileName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/sourcefilename) { get; } | Όνομα αρχείου του πηγαίου εγγράφου που μετατρέπεται. Όταν η πηγή παρέχεται ως ροή που δεν είναι FileStream, αυτό περιέχει ένα δημιουργημένο αναγνωριστικό αντί για πραγματικό όνομα αρχείου. |
| [SubstituteFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/substitutefontname) { get; } | Όνομα της γραμματοσειράς που χρησιμοποιείται ως αντικατάσταση. Μπορεί να είναι `null` για έγγραφα των οποίων η μηχανή αναφέρει την αντικατάσταση μόνο ως περιγραφικό κείμενο — σε αυτήν την περίπτωση διαβάστε [`Reason`](./reason). |

### Δείτε επίσης

* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
