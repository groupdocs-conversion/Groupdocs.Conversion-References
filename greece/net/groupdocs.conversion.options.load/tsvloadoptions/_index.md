---
title: "TsvLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων Tsv."
type: docs
weight: 2850
url: /el/net/groupdocs.conversion.options.load/tsvloadoptions/
---
## TsvLoadOptions class

Επιλογές για τη φόρτωση εγγράφων Tsv.

```csharp
public sealed class TsvLoadOptions : SpreadsheetLoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [TsvLoadOptions](tsvloadoptions)() | Αρχικοποιεί νέα παρουσία της κlassς [`TsvLoadOptions`](../tsvloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AllColumnsInOnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/allcolumnsinonepagepersheet) { get; set; } | Εάν το AllColumnsInOnePagePerSheet είναι true, όλο το περιεχόμενο των στηλών ενός φύλλου θα εξάγεται σε μία μόνο σελίδα στο αποτέλεσμα. Το πλάτος του μεγέθους χαρτιού του pagesetup θα είναι άκυρο, ενώ οι άλλες ρυθμίσεις του pagesetup θα παραμείνουν σε ισχύ. |
| [AutoFitRows](../../groupdocs.conversion.options.load/spreadsheetloadoptions/autofitrows) { get; set; } | Αυτόματη προσαρμογή όλων των γραμμών κατά τη μετατροπή |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Καθορίζει αν θα ελέγχεται ο περιορισμός του αρχείου Excel όταν ο χρήστης τροποποιεί αντικείμενα σχετιζόμενα με κελιά. Για παράδειγμα, το Excel δεν επιτρέπει την εισαγωγή τιμής συμβολοσειράς μεγαλύτερης από 32K. Όταν εισάγετε μια τιμή μεγαλύτερη από 32K, εάν αυτή η ιδιότητα είναι true, θα λάβετε μια Exception. Εάν αυτή η ιδιότητα είναι false, θα αποδεχθούμε την εισαγόμενη τιμή συμβολοσειράς ως τιμή του κελιού, ώστε αργότερα να μπορείτε να εξάγετε την πλήρη τιμή συμβολοσειράς για άλλες μορφές αρχείων όπως CSV. Ωστόσο, εάν έχετε ορίσει τέτοια τιμή που είναι μη έγκυρη για τη μορφή αρχείου Excel, δεν πρέπει να αποθηκεύσετε το βιβλίο εργασίας ως μορφή αρχείου Excel αργότερα. Διαφορετικά μπορεί να προκύψει απρόσμενο σφάλμα στο παραγόμενο αρχείο Excel. |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearbuiltindocumentproperties) { get; set; } | Αφαιρεί ενσωματωμένες ιδιότητες μεταδεδομένων από το έγγραφο. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearcustomdocumentproperties) { get; set; } | Αφαιρεί προσαρμοσμένες ιδιότητες μεταδεδομένων από το έγγραφο. |
| [ColumnsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/columnsperpage) { get; set; } | Διαίρεση ενός φύλλου εργασίας σε σελίδες ανά στήλες. Η προεπιλογή είναι 0, χωρίς σελιδοποίηση. |
| [ConvertOwned](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowned) { get; set; } | Υλοποιεί [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Η προεπιλογή είναι false |
| [ConvertOwner](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowner) { get; set; } | Υλοποιεί [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Η προεπιλογή είναι true |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Μετατροπή συγκεκριμένου εύρους κατά τη μετατροπή σε μορφή διαφορετική από το λογιστικό φύλλο. Παράδειγμα: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Ανάκτηση ή ορισμός των πληροφοριών πολιτισμού του συστήματος τη στιγμή που φορτώνεται το αρχείο |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Προεπιλεγμένη γραμματοσειρά για το έγγραφο λογιστικού φύλλου. Η παρακάτω γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει κάποια γραμματοσειρά. |
| [Depth](../../groupdocs.conversion.options.load/spreadsheetloadoptions/depth) { get; set; } | Υλοποιεί [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Προεπιλογή: 1 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Αντικατάσταση συγκεκριμένων γραμματοσειρών κατά τη μετατροπή του εγγράφου λογιστικού φύλλου. |
| [Format](../../groupdocs.conversion.options.load/tsvloadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| [IgnoreFormulaCalculationErrors](../../groupdocs.conversion.options.load/spreadsheetloadoptions/ignoreformulacalculationerrors) { get; set; } | Δείχνει αν θα αγνοούνται τα σφάλματα υπολογισμού τύπων. Το σφάλμα μπορεί να είναι μη υποστηριζόμενη λειτουργία, εξωτερικοί σύνδεσμοι κ.λπ. Η προεπιλογή είναι false. |
| [MarginSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/marginsettings) { get; set; } | Ρυθμίσεις περιθωρίων σελίδας |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Εάν το OnePagePerSheet είναι true, το περιεχόμενο του φύλλου θα μετατραπεί σε μία σελίδα στο έγγραφο PDF. Η προεπιλεγμένη τιμή είναι true. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Εάν είναι True και γίνεται μετατροπή σε PDF, η μετατροπή βελτιστοποιείται για μικρότερο μέγεθος αρχείου παρά για ποιότητα εκτύπωσης. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Ορίστε κωδικό πρόσβασης για την αφαίρεση προστασίας του προστατευμένου εγγράφου. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/spreadsheetloadoptions/preservedocumentstructure) { get; set; } | Καθορίζει αν η δομή του εγγράφου πρέπει να διατηρηθεί κατά τη μετατροπή σε PDF (η προεπιλογή είναι false). |
| [PrintComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/printcomments) { get; set; } | Αναπαριστά τον τρόπο εκτύπωσης των σχολίων με το φύλλο. Η προεπιλογή είναι PrintNoComments. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/resetfontfolders) { get; set; } | Επαναφορά φακέλων γραμματοσειρών πριν τη φόρτωση του εγγράφου |
| [RowsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/rowsperpage) { get; set; } | Διαίρεση ενός φύλλου εργασίας σε σελίδες ανά γραμμές. Η προεπιλογή είναι 0, χωρίς σελιδοποίηση. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | Λίστα δεικτών φύλλων προς μετατροπή. Οι δείκτες πρέπει να είναι μηδενικής βάσης |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Όνομα φύλλου προς μετατροπή |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Εμφάνιση γραμμών πλέγματος κατά τη μετατροπή αρχείων Excel. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Εμφάνιση κρυφών φύλλων κατά τη μετατροπή αρχείων Excel. |
| [SizeSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sizesettings) { get; set; } | Ρυθμίσεις μεγέθους σελίδας |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Παράλειψη κενών γραμμών και στηλών κατά τη μετατροπή. Η προεπιλογή είναι True. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipexternalresources) { get; set; } | Υλοποιεί [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [SkipFooters](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipfooters) { get; set; } | Παράλειψη υποσέλιδων κατά τη μετατροπή εγγράφων λογιστικού φύλλου. Προεπιλογή: false. |
| [SkipHeaders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipheaders) { get; set; } | Παράλειψη κεφαλίδων κατά τη μετατροπή εγγράφων λογιστικού φύλλου. Προεπιλογή: false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/whitelistedresources) { get; set; } | Υλοποιεί [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
