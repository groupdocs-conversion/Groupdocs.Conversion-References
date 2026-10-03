---
title: "DatabaseFileType"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει έγγραφα βάσεων δεδομένων. Περιλαμβάνει τους ακόλουθους τύπους αρχείων Nsf./databasefiletype/nsfLog./databasefiletype/logSql./databasefiletype/sql"
type: docs
weight: 1090
url: /el/net/groupdocs.conversion.filetypes/databasefiletype/
---
## DatabaseFileType class

Ορίζει έγγραφα βάσεων δεδομένων. Περιλαμβάνει τους ακόλουθους τύπους αρχείων: [`Nsf`](./nsf)[`Log`](./log)[`Sql`](./sql)

```csharp
public sealed class DatabaseFileType : FileType
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DatabaseFileType](databasefiletype)() | Κατασκευαστής σειριοποίησης |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Περιγραφή τύπου αρχείου |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Η επέκταση αρχείου |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Η οικογένεια αρχείου |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Η μορφή αρχείου |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Συγκρίνει το τρέχον αντικείμενο με άλλο. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Υλοποιεί [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Αναπαράσταση συμβολοσειράς |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| static readonly [Log](../../groupdocs.conversion.filetypes/databasefiletype/log) | Ένα αρχείο με επέκταση .log περιέχει λίστα απλού κειμένου με χρονική σήμανση. Συνήθως, ορισμένες λεπτομέρειες δραστηριότητας καταγράφονται από το λογισμικό ή τα λειτουργικά συστήματα για να βοηθήσουν τους προγραμματιστές ή τους χρήστες να παρακολουθήσουν τι συνέβαινε σε μια συγκεκριμένη χρονική περίοδο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/database/log). |
| static readonly [Nsf](../../groupdocs.conversion.filetypes/databasefiletype/nsf) | Ένα αρχείο με επέκταση .nsf (Notes Storage Facility) είναι μια μορφή αρχείου βάσης δεδομένων που χρησιμοποιείται από το λογισμικό IBM Notes, το οποίο προηγουμένως ήταν γνωστό ως Lotus Notes. Ορίζει το σχήμα για την αποθήκευση διαφορετικών τύπων αντικειμένων όπως email, ραντεβού, έγγραφα, φόρμες και προβολές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/database/nsf). |
| static readonly [Sql](../../groupdocs.conversion.filetypes/databasefiletype/sql) | Ένα αρχείο με επέκταση .sql είναι ένα αρχείο Structured Query Language (SQL) που περιέχει κώδικα για εργασία με σχεσιακές βάσεις δεδομένων. Χρησιμοποιείται για τη σύνταξη δηλώσεων SQL για λειτουργίες CRUD (Create, Read, Update, and Delete) σε βάσεις δεδομένων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/database/sql). |

### Δείτε επίσης

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
