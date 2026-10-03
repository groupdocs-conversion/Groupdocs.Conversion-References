---
title: "EmailFileType"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει μορφές αρχείων Email που χρησιμοποιούνται από εφαρμογές email για την αποθήκευση των διαφόρων δεδομένων τους, συμπεριλαμβανομένων των μηνυμάτων email, συνημμένων, φακέλων, βιβλίων διευθύνσεων κ.λπ. Περιλαμβάνει τους ακόλουθους τύπους αρχείων Eml./emailfiletype/eml Emlx./emailfiletype/emlx Msg./emailfiletype/msg Vcf./emailfiletype/vcf. Mbox./emailfiletype/mbox. Pst./emailfiletype/pst. Ost./emailfiletype/ost. Olm./emailfiletype/olm. Μάθετε περισσότερα για τις μορφές Email εδώhttps//wiki.fileformat.com/email."
type: docs
weight: 1120
url: /el/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Ορίζει μορφές αρχείων Email που χρησιμοποιούνται από εφαρμογές email για την αποθήκευση των διαφόρων δεδομένων τους, συμπεριλαμβανομένων των μηνυμάτων email, συνημμένων, φακέλων, βιβλίων διευθύνσεων κ.λπ. Περιλαμβάνει τους ακόλουθους τύπους αρχείων: [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Vcf`](./vcf). [`Mbox`](./mbox). [`Pst`](./pst). [`Ost`](./ost). [`Olm`](./olm). Μάθετε περισσότερα για τις μορφές Email [εδώ](https://wiki.fileformat.com/email).

```csharp
public sealed class EmailFileType : FileType
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [EmailFileType](emailfiletype)() | Κατασκευαστής σειριοποίησης |

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
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | Η μορφή αρχείου EML αντιπροσωπεύει μηνύματα email που αποθηκεύονται χρησιμοποιώντας το Outlook και άλλες σχετικές εφαρμογές. Σχεδόν όλοι οι πελάτες email υποστηρίζουν αυτή τη μορφή αρχείου λόγω της συμμόρφωσής της με το πρότυπο RFC-822 Internet Message Format Standard. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/email/eml). |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | Η μορφή αρχείου EMLX υλοποιείται και αναπτύσσεται από την Apple. Η εφαρμογή Apple Mail χρησιμοποιεί τη μορφή αρχείου EMLX για την εξαγωγή των email. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/email/emlx). |
| static readonly [Ics](../../groupdocs.conversion.filetypes/emailfiletype/ics) | Η μορφή αρχείου ICS (iCalendar) χρησιμοποιείται για την αναπαράσταση και ανταλλαγή πληροφοριών ημερολογίου και προγραμματισμού, όπως γεγονότα, εργασίες και δεδομένα ελεύθερου/απασχολημένου χρόνου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/email/ics). |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | Η μορφή αρχείου MBox είναι ένας γενικός όρος που αντιπροσωπεύει ένα δοχείο για τη συλλογή ηλεκτρονικών μηνυμάτων. Τα μηνύματα αποθηκεύονται μέσα στο δοχείο μαζί με τα συνημμένα τους. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/email/mbox/). |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | Το MSG είναι μια μορφή αρχείου που χρησιμοποιείται από το Microsoft Outlook και το Exchange για την αποθήκευση μηνυμάτων email, επαφών, ραντεβού ή άλλων εργασιών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/email/msg). |
| static readonly [Olm](../../groupdocs.conversion.filetypes/emailfiletype/olm) | Ένα αρχείο με επέκταση .olm είναι ένα αρχείο Microsoft Outlook για το λειτουργικό σύστημα macOS. Ένα αρχείο OLM αποθηκεύει μηνύματα email, ημερολόγια, δεδομένα ημερολογίου και άλλους τύπους δεδομένων εφαρμογών. Αυτά είναι παρόμοια με τα αρχεία PST που χρησιμοποιούνται από το Outlook στα Windows. Ωστόσο, τα αρχεία OLM που δημιουργούνται από το Outlook για Mac δεν μπορούν να ανοιχτούν στο Outlook για Windows. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/email/olm). |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | Τα αρχεία OST ή Offline Storage αντιπροσωπεύουν τα δεδομένα του γραμματοκιβωτίου του χρήστη σε λειτουργία εκτός σύνδεσης στον τοπικό υπολογιστή μετά την εγγραφή σε Exchange Server χρησιμοποιώντας το Microsoft Outlook. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/email/ost). |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | Τα αρχεία με επέκταση .PST αντιπροσωπεύουν τα Outlook Personal Storage Files (επίσης γνωστά ως Personal Storage Table) που αποθηκεύουν διάφορες πληροφορίες χρήστη. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/email/pst). |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | Το VCF (Virtual Card Format) ή vCard είναι μια ψηφιακή μορφή αρχείου για την αποθήκευση πληροφοριών επαφών. Η μορφή αυτή χρησιμοποιείται ευρέως για ανταλλαγή δεδομένων μεταξύ δημοφιλών εφαρμογών ανταλλαγής πληροφοριών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/email/vcf). |

### Δείτε επίσης

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
