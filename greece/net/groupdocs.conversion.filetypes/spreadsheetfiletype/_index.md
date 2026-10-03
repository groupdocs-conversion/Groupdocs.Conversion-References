---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει έγγραφα Spreadsheet. Περιλαμβάνει τους ακόλουθους τύπους αρχείων Csv./spreadsheetfiletype/csv Fods./spreadsheetfiletype/fods Ods./spreadsheetfiletype/ods Ots./spreadsheetfiletype/ots Tsv./spreadsheetfiletype/tsv Xlam./spreadsheetfiletype/xlam Xls./spreadsheetfiletype/xls Xlsb./spreadsheetfiletype/xlsb Xlsm./spreadsheetfiletype/xlsm Xlsx./spreadsheetfiletype/xlsx Xlt./spreadsheetfiletype/xlt Xltm./spreadsheetfiletype/xltm Xltx./spreadsheetfiletype/xltx. Μάθετε περισσότερα για τις μορφές Spreadsheet εδώhttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 1240
url: /el/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Ορίζει έγγραφα Spreadsheet. Περιλαμβάνει τους ακόλουθους τύπους αρχείων: [`Csv`](./csv), [`Fods`](./fods), [`Ods`](./ods), [`Ots`](./ots), [`Tsv`](./tsv), [`Xlam`](./xlam), [`Xls`](./xls), [`Xlsb`](./xlsb), [`Xlsm`](./xlsm), [`Xlsx`](./xlsx), [`Xlt`](./xlt), [`Xltm`](./xltm), [`Xltx`](./xltx). Μάθετε περισσότερα για τις μορφές Spreadsheet [εδώ](https://wiki.fileformat.com/spreadsheet).

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Κατασκευαστής σειριοποίησης |

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
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | Τα αρχεία με επέκταση CSV (Comma Separated Values) αντιπροσωπεύουν αρχεία απλού κειμένου που περιέχουν εγγραφές δεδομένων με τιμές χωρισμένες με κόμμα. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | Το DIF σημαίνει Data Interchange Format που χρησιμοποιείται για την εισαγωγή/εξαγωγή δεδομένων λογιστικών φύλλων μεταξύ διαφορετικών εφαρμογών. Αυτές περιλαμβάνουν το Microsoft Excel, το OpenOffice Calc, το StarCalc και πολλά άλλα. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/dif). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/flatopc) | Το Flat OPC Excel είναι Office Open XML SpreadsheetML αποθηκευμένο σε επίπεδο αρχείο XML αντί για πακέτο ZIP. |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | Ένα αρχείο με επέκταση .fods είναι ένας τύπος μορφότυπου OpenDocument Spreadsheet που αποθηκεύει δεδομένα σε σειρές και στήλες. Η μορφή ορίζεται ως μέρος των προδιαγραφών ODF 1.2 που δημοσιεύονται και συντηρούνται από το OASIS. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/fods). |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | Τα αρχεία με επέκταση .numbers ταξινομούνται ως τύπος αρχείου λογιστικού φύλλου, γι' αυτό είναι παρόμοια με τα αρχεία .xlsx· αλλά τα αρχεία Numbers δημιουργούνται με τη χρήση του λογιστικού λογισμικού Apple iWork Numbers. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/spreadsheet/numbers). |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | Τα αρχεία με επέκταση ODS αντιπροσωπεύουν μορφότυπο OpenDocument Spreadsheet που μπορεί να επεξεργαστεί από τον χρήστη. Τα δεδομένα αποθηκεύονται μέσα σε αρχείο ODF σε σειρές και στήλες. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | Ένα αρχείο με επέκταση .ots είναι ένα πρότυπο OpenDocument Spreadsheet που δημιουργείται με το λογισμικό εφαρμογής Calc που περιλαμβάνεται στο Apache OpenOffice. Το λογισμικό εφαρμογής Calc είναι παρόμοιο με το Excel που διατίθεται στο Microsoft Office. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/ots). |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | Ο μορφότυπος αρχείου SXC (Sun XML Calc) ανήκει σε μια σουίτα γραφείου που ονομάζεται OpenOffice.org. Αυτός ο μορφότυπος εξυπηρετεί γενικά τις ανάγκες λογιστικών φύλλων των χρηστών, καθώς είναι ένας μορφότυπος αρχείου λογιστικού φύλλου βασισμένος σε XML. Η μορφή SXC υποστηρίζει τύπους, συναρτήσεις, μακροεντολές και διαγράμματα μαζί με το DataPilot. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/sxc). |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Μια μορφή αρχείου Tab-Separated Values (TSV) αντιπροσωπεύει δεδομένα που διαχωρίζονται με καρτέλες σε απλό κείμενο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | Το XLAM είναι ένα αρχείο Macro-Enabled Add-In που χρησιμοποιείται για την προσθήκη νέων λειτουργιών στα υπολογιστικά φύλλα. Ένα Add-In είναι ένα συμπληρωματικό πρόγραμμα που εκτελεί πρόσθετο κώδικα και παρέχει επιπλέον λειτουργικότητα για τα υπολογιστικά φύλλα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/spreadsheet/xlam/). |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | Το XLS αντιπροσωπεύει τη μορφή Excel Binary File Format. Τέτοια αρχεία μπορούν να δημιουργηθούν από το Microsoft Excel καθώς και από άλλα παρόμοια προγράμματα υπολογιστικών φύλλων όπως το OpenOffice Calc ή το Apple Numbers. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | Η μορφή αρχείου XLSB καθορίζει τη μορφή Excel Binary File Format, η οποία είναι μια συλλογή εγγραφών και δομών που καθορίζουν το περιεχόμενο του βιβλίου εργασίας του Excel. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | Το XLSM είναι ένας τύπος αρχείων υπολογιστικών φύλλων που υποστηρίζουν μακροεντολές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | Το XLSX είναι μια γνωστή μορφή για έγγραφα Microsoft Excel που εισήχθη από τη Microsoft με την κυκλοφορία του Microsoft Office 2007. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | Τα αρχεία με την επέκταση .XLT είναι αρχεία προτύπων που δημιουργήθηκαν με το Microsoft Excel, το οποίο είναι μια εφαρμογή υπολογιστικών φύλλων που αποτελεί μέρος της σουίτας Microsoft Office. Το Microsoft Office 97-2003 υποστήριζε τη δημιουργία νέων αρχείων XLT καθώς και το άνοιγμά τους. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | Η επέκταση αρχείου XLTM αντιπροσωπεύει αρχεία που δημιουργούνται από το Microsoft Excel ως πρότυπα με ενεργοποιημένες μακροεντολές. Τα αρχεία XLTM είναι παρόμοια με τα XLTX στη δομή, εκτός από το ότι τα δεύτερα δεν υποστηρίζουν τη δημιουργία προτύπων με μακροεντολές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | Το αρχείο XLTX αντιπροσωπεύει το Microsoft Excel Template που βασίζεται στις προδιαγραφές της μορφής αρχείου Office OpenXML. Χρησιμοποιείται για τη δημιουργία ενός τυπικού αρχείου προτύπου που μπορεί να χρησιμοποιηθεί για τη δημιουργία αρχείων XLSX που εμφανίζουν τις ίδιες ρυθμίσεις όπως ορίζονται στο αρχείο XLTX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/xltx). |

### Δείτε επίσης

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
