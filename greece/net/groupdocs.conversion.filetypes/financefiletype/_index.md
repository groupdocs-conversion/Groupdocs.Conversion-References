---
title: "FinanceFileType"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει έγγραφα Χρηματοοικονομικών. Περιλαμβάνει τους ακόλουθους τύπους Xbrl./financefiletype/xbrlIXbrl./financefiletype/ixbrlOfx./financefiletype/ofx Μάθετε περισσότερα για τις μορφές Χρηματοοικονομικών εδώhttps//docs.fileformat.com/finance/."
type: docs
weight: 1140
url: /el/net/groupdocs.conversion.filetypes/financefiletype/
---
## FinanceFileType class

Ορίζει έγγραφα Χρηματοοικονομικών. Περιλαμβάνει τους ακόλουθους τύπους: [`Xbrl`](./xbrl)[`IXbrl`](./ixbrl)[`Ofx`](./ofx) Μάθετε περισσότερα για τις μορφές Χρηματοοικονομικών [εδώ](https://docs.fileformat.com/finance/).

```csharp
public sealed class FinanceFileType : FileType
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [FinanceFileType](financefiletype)() | Κατασκευαστής σειριοποίησης |

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
| static readonly [IXbrl](../../groupdocs.conversion.filetypes/financefiletype/ixbrl) | Στο iXBRL, τα περιεχόμενα του XBRL είναι ενσωματωμένα σε μορφή αρχείου xHTML που χρησιμοποιεί ετικέτες XML. Όπως το XBRL, είναι το ριζικό στοιχείο των αρχείων iXBRL. Η μορφή XHTML αντιπροσωπεύει τα περιεχόμενά της ως συλλογή διαφορετικών τύπων εγγράφων και μονάδων. Όλα τα αρχεία σε XHTML βασίζονται στη μορφή αρχείου XML και συμμορφώνονται με τα πρότυπα εγγράφων XML. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/finance/ixbrl/). |
| static readonly [Ofx](../../groupdocs.conversion.filetypes/financefiletype/ofx) | Το Open Financial Exchange (OFX) είναι μια μορφή ροής δεδομένων για την ανταλλαγή χρηματοοικονομικών πληροφοριών που εξελίχθηκε από το Open Financial Connectivity (OFC) της Microsoft και τις μορφές αρχείων Open Exchange της Intuit. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://en.wikipedia.org/wiki/Open_Financial_Exchange). |
| static readonly [Xbrl](../../groupdocs.conversion.filetypes/financefiletype/xbrl) | Το XBRL είναι ένα ανοιχτό διεθνές πρότυπο για ψηφιακή επιχειρηματική αναφορά που χρησιμοποιείται ευρέως παγκοσμίως. Είναι μια γλώσσα βασισμένη σε XML που χρησιμοποιεί στοιχεία XBRL, γνωστά ως ετικέτες, για να περιγράψει κάθε στοιχείο επιχειρηματικών δεδομένων ώστε να διαμορφώσει δεδομένα για ταξινόμηση και ανάλυση αναφορών. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/finance/xbrl/). |

### Δείτε επίσης

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
