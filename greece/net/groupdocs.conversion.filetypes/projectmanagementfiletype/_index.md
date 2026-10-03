---
title: "ΤύποςΑρχείουΔιαχείρισηςΈργου"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει μορφές αρχείων έργου που δημιουργούνται από λογισμικό διαχείρισης έργου όπως το Microsoft Project, Primavera P6 κλπ. Ένα αρχείο έργου είναι μια συλλογή εργασιών, πόρων και του προγραμματισμού τους για να παραχθεί ένα μετρήσιμο αποτέλεσμα με τη μορφή προϊόντος ή υπηρεσίας. Έγγραφα διαχείρισης έργου. Περιλαμβάνει τους ακόλουθους τύπους αρχείων Mpp./projectmanagementfiletype/mpp Mpt./projectmanagementfiletype/mpt Mpx./projectmanagementfiletype/mpx. Μάθετε περισσότερα για τις μορφές διαχείρισης έργου εδώhttps//wiki.fileformat.com/projectmanagement."
type: docs
weight: 1220
url: /el/net/groupdocs.conversion.filetypes/projectmanagementfiletype/
---
## ProjectManagementFileType class

Ορίζει μορφές αρχείων έργου που δημιουργούνται από λογισμικό διαχείρισης έργου όπως το Microsoft Project, Primavera P6 κλπ. Ένα αρχείο έργου είναι μια συλλογή εργασιών, πόρων και του προγραμματισμού τους για να παραχθεί ένα μετρήσιμο αποτέλεσμα με τη μορφή προϊόντος ή υπηρεσίας. Έγγραφα διαχείρισης έργου. Περιλαμβάνει τους ακόλουθους τύπους αρχείων: [`Mpp`](./mpp), [`Mpt`](./mpt), [`Mpx`](./mpx). Μάθετε περισσότερα για τις μορφές διαχείρισης έργου [εδώ](https://wiki.fileformat.com/project-management).

```csharp
public sealed class ProjectManagementFileType : FileType
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [ProjectManagementFileType](projectmanagementfiletype)() | Κατασκευαστής σειριοποίησης |

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
| static readonly [Mpp](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpp) | Το MPP είναι αρχείο δεδομένων Microsoft Project που αποθηκεύει πληροφορίες σχετικές με τη διαχείριση έργου με ολοκληρωμένο τρόπο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/project-management/mpp). |
| static readonly [Mpt](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpt) | Τα αρχεία προτύπου Microsoft Project περιέχουν βασικές πληροφορίες και δομή μαζί με ρυθμίσεις εγγράφου για τη δημιουργία αρχείων .MPP. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/project-management/mpt). |
| static readonly [Mpx](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpx) | Το Microsoft Exchange File Format είναι μια μορφή αρχείου ASCII για τη μεταφορά πληροφοριών έργου μεταξύ Microsoft Project (MSP) και άλλων εφαρμογών που υποστηρίζουν τη μορφή αρχείου MPX, όπως Primavera Project Planner, Sciforma και Timerline Precision Estimating. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/project-management/mpx). |
| static readonly [Xer](../../groupdocs.conversion.filetypes/projectmanagementfiletype/xer) | Η μορφή αρχείου XER είναι μια ιδιόκτητη μορφή αρχείου έργου που χρησιμοποιείται από την εφαρμογή προγραμματισμού και διαχείρισης έργου Primavera P6. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/project-management/xer). |

### Δείτε επίσης

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
