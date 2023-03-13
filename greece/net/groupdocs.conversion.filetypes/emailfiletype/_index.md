---
title: EmailFileType
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Καθορίζει μορφές αρχείων email που χρησιμοποιούνται από εφαρμογές email για την αποθήκευση των διαφόρων δεδομένων τους συμπεριλαμβανομένων μηνυμάτων email συνημμένων φακέλων βιβλίων διευθύνσεων κ.λπ. Περιλαμβάνει τους ακόλουθους τύπους αρχείων Eml./emailfiletype/eml  Emlx./emailfiletype/emlx  Msg./emailfiletype/msg  Vcf./emailfiletype/vcf . Mbox./emailfiletype/mbox . Pst./emailfiletype/pst . Ost./emailfiletype/ost . Μάθετε περισσότερα σχετικά με τις μορφές ηλεκτρονικού ταχυδρομείουεδώhttps//wiki.fileformat.com/email .
type: docs
weight: 920
url: /el/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Καθορίζει μορφές αρχείων email που χρησιμοποιούνται από εφαρμογές email για την αποθήκευση των διαφόρων δεδομένων τους, συμπεριλαμβανομένων μηνυμάτων email, συνημμένων, φακέλων, βιβλίων διευθύνσεων κ.λπ. Περιλαμβάνει τους ακόλουθους τύπους αρχείων: [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Vcf`](./vcf) . [`Mbox`](./mbox) . [`Pst`](./pst) . [`Ost`](./ost) . Μάθετε περισσότερα σχετικά με τις μορφές ηλεκτρονικού ταχυδρομείου[εδώ](https://wiki.fileformat.com/email) .

```csharp
public sealed class EmailFileType : FileType
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [EmailFileType](emailfiletype)() | Κατασκευαστής σειριοποίησης |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Περιγραφή τύπου αρχείου |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Η επέκταση αρχείου |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Η οικογένεια αρχείων |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Η μορφή αρχείου |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Συγκρίνει το τρέχον αντικείμενο με άλλο. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Εξυπηρετεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Αναπαράσταση συμβολοσειράς |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | Η μορφή αρχείου EML αντιπροσωπεύει μηνύματα email που έχουν αποθηκευτεί με χρήση του Outlook και άλλων σχετικών εφαρμογών. Σχεδόν όλοι οι πελάτες αποστολής μηνυμάτων ηλεκτρονικού ταχυδρομείου υποστηρίζουν αυτήν τη μορφή αρχείου για τη συμμόρφωσή της με το πρότυπο μορφής μηνυμάτων Internet RFC-822. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/email/eml) . |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | Η μορφή αρχείου EMX υλοποιείται και αναπτύσσεται από την Apple. Η εφαρμογή Apple Mail χρησιμοποιεί τη μορφή αρχείου EMLX για την εξαγωγή των email. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/email/emlx) . |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | Η μορφή αρχείου MBox είναι ένας γενικός όρος που αντιπροσωπεύει ένα κοντέινερ για τη συλλογή μηνυμάτων ηλεκτρονικού ταχυδρομείου. Τα μηνύματα αποθηκεύονται μέσα στο κοντέινερ μαζί με τα συνημμένα τους. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | Το MSG είναι μια μορφή αρχείου που χρησιμοποιείται από το Microsoft Outlook και το Exchange για την αποθήκευση μηνυμάτων email, επαφών, συναντήσεων ή άλλων εργασιών. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/email/msg) . |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | Το OST ή τα αρχεία αποθήκευσης εκτός σύνδεσης αντιπροσωπεύουν τα δεδομένα γραμματοκιβωτίου του χρήστη σε λειτουργία εκτός σύνδεσης σε τοπικό μηχάνημα κατά την εγγραφή στον Exchange Server χρησιμοποιώντας το Microsoft Outlook. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/email/ost) . |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | Τα αρχεία με επέκταση .PST αντιπροσωπεύουν τα προσωπικά αρχεία αποθήκευσης του Outlook (ονομάζονται επίσης Personal Storage Table) που αποθηκεύουν ποικιλία πληροφοριών χρήστη. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/email/pst) . |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | Το VCF (Virtual Card Format) ή vCard είναι μια ψηφιακή μορφή αρχείου για την αποθήκευση πληροφοριών επικοινωνίας. Η μορφή χρησιμοποιείται ευρέως για ανταλλαγή δεδομένων μεταξύ δημοφιλών εφαρμογών ανταλλαγής πληροφοριών. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/email/vcf) . |

### Δείτε επίσης

* class [FileType](../filetype)
* χώρος ονομάτων [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* συνέλευση [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
