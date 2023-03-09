---
title: SpreadsheetFileType
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Καθορίζει έγγραφα υπολογιστικού φύλλου. Περιλαμβάνει τους ακόλουθους τύπους αρχείων Csv./spreadsheetfiletype/csv  Fods./spreadsheetfiletype/fods  Ods./spreadsheetfiletype/ods  Ots./spreadsheetfiletype/ots  Tsv./spreadsheetfiletype/tsv  Xlam./spreadsheetfiletype/xlam  Xls./spreadsheetfiletype/xls  Xlsb./spreadsheetfiletype/xlsb  Xlsm./spreadsheetfiletype/xlsm  Xlsx./spreadsheetfiletype/xlsx  Xlt./spreadsheetfiletype/xlt  Xltm./spreadsheetfiletype/xltm  Xltx./spreadsheetfiletype/xltx . Μάθετε περισσότερα σχετικά με τις μορφές υπολογιστικών φύλλωνεδώhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 1050
url: /el/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Καθορίζει έγγραφα υπολογιστικού φύλλου. Περιλαμβάνει τους ακόλουθους τύπους αρχείων: [`Csv`](./csv) , [`Fods`](./fods) , [`Ods`](./ods) , [`Ots`](./ots) , [`Tsv`](./tsv) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . Μάθετε περισσότερα σχετικά με τις μορφές υπολογιστικών φύλλων[εδώ](https://wiki.fileformat.com/spreadsheet) .

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Κατασκευαστής σειριοποίησης |

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
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | Τα αρχεία με επέκταση CSV (Τιμές διαχωρισμένες με κόμματα) αντιπροσωπεύουν αρχεία απλού κειμένου που περιέχουν εγγραφές δεδομένων με τιμές διαχωρισμένες με κόμμα. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | Το DIF σημαίνει Μορφή ανταλλαγής δεδομένων που χρησιμοποιείται για την εισαγωγή/εξαγωγή δεδομένων υπολογιστικών φύλλων μεταξύ διαφορετικών εφαρμογών. Αυτά περιλαμβάνουν το Microsoft Excel, το OpenOffice Calc, το StarCalc και πολλά άλλα. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/dif) . |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | Ένα αρχείο με επέκταση .fods είναι ένας τύπος μορφής εγγράφου υπολογιστικού φύλλου OpenDocument που αποθηκεύει δεδομένα σε σειρές και στήλες. Η μορφή καθορίζεται ως μέρος των προδιαγραφών ODF 1.2 που δημοσιεύονται και διατηρούνται από το OASIS. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/fods) . |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | Τα αρχεία με επέκταση .numbers ταξινομούνται ως τύπος αρχείου υπολογιστικού φύλλου, γι' αυτό είναι παρόμοια με τα αρχεία .xlsx. αλλά τα αρχεία Numbers δημιουργούνται χρησιμοποιώντας το λογισμικό υπολογιστικών φύλλων Apple iWork Numbers. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/spreadsheet/numbers) . |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | Τα αρχεία με επέκταση ODS αντιπροσωπεύουν τη μορφή εγγράφου υπολογιστικού φύλλου OpenDocument που είναι επεξεργάσιμα από τον χρήστη. Τα δεδομένα αποθηκεύονται μέσα στο αρχείο ODF σε σειρές και στήλες. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | Ένα αρχείο με επέκταση .ots είναι ένα αρχείο προτύπου υπολογιστικού φύλλου OpenDocument που δημιουργείται με το λογισμικό εφαρμογής Calc που περιλαμβάνεται στο Apache OpenOffice. Το λογισμικό εφαρμογής Calc είναι παρόμοιο με το Excel που διατίθεται στο Microsoft Office. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/ots) . |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | Η μορφή αρχείου SXC(Sun XML Calc) ανήκει σε μια σουίτα γραφείου που ονομάζεται OpenOffice.org. Αυτή η μορφή γενικά ασχολείται με τις ανάγκες υπολογιστικών φύλλων των χρηστών καθώς είναι μια μορφή αρχείου υπολογιστικού φύλλου που βασίζεται σε XML. Η μορφή SXC υποστηρίζει τύπους, συναρτήσεις, μακροεντολές και γραφήματα μαζί με το DataPilot. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/sxc) . |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Μια μορφή αρχείου τιμών διαχωρισμένων με καρτέλες (TSV) αντιπροσωπεύει δεδομένα διαχωρισμένα με καρτέλες σε μορφή απλού κειμένου. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | Το XLAM είναι ένα αρχείο πρόσθετου με δυνατότητα μακροεντολής που χρησιμοποιείται για την προσθήκη νέων λειτουργιών σε υπολογιστικά φύλλα. Το πρόσθετο είναι ένα συμπληρωματικό πρόγραμμα που εκτελεί πρόσθετο κώδικα και παρέχει πρόσθετη λειτουργικότητα για υπολογιστικά φύλλα. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/spreadsheet/xlam/) . |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | Το XLS αντιπροσωπεύει τη μορφή δυαδικού αρχείου του Excel. Τέτοια αρχεία μπορούν να δημιουργηθούν από το Microsoft Excel καθώς και από άλλα παρόμοια προγράμματα υπολογιστικών φύλλων όπως το OpenOffice Calc ή το Apple Numbers. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | Η μορφή αρχείου XLSB καθορίζει τη μορφή δυαδικού αρχείου του Excel, η οποία είναι μια συλλογή εγγραφών και δομών που καθορίζουν το περιεχόμενο του βιβλίου εργασίας του Excel. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | Το XLSM είναι ένας τύπος αρχείων υπολογιστικών φύλλων που υποστηρίζουν μακροεντολές. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | Το XLSX είναι μια πολύ γνωστή μορφή για έγγραφα του Microsoft Excel που εισήχθη από τη Microsoft με την κυκλοφορία του Microsoft Office 2007. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | Τα αρχεία με επέκταση .XLT είναι αρχεία προτύπων που δημιουργούνται με το Microsoft Excel, το οποίο είναι μια εφαρμογή υπολογιστικών φύλλων που διατίθεται ως μέρος της σουίτας του Microsoft Office. Το Microsoft Office 97-2003 υποστήριξε τη δημιουργία νέων αρχείων XLT καθώς και το άνοιγμα αυτών. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | Η επέκταση αρχείου XLTM αντιπροσωπεύει αρχεία που δημιουργούνται από το Microsoft Excel ως αρχεία προτύπων με δυνατότητα Macro. Τα αρχεία XLTM είναι παρόμοια με τα XLTX σε δομή, εκτός από το ότι το τελευταίο δεν υποστηρίζει τη δημιουργία αρχείων προτύπων με μακροεντολές. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | Το αρχείο XLTX αντιπροσωπεύει το πρότυπο Microsoft Excel που βασίζεται στις προδιαγραφές μορφής αρχείου του Office OpenXML. Χρησιμοποιείται για τη δημιουργία ενός τυπικού αρχείου προτύπου που μπορεί να χρησιμοποιηθεί για τη δημιουργία αρχείων XLSX που εμφανίζουν τις ίδιες ρυθμίσεις με αυτές που καθορίζονται στο αρχείο XLTX. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/xltx) . |

### Δείτε επίσης

* class [FileType](../filetype)
* χώρος ονομάτων [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* συνέλευση [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
