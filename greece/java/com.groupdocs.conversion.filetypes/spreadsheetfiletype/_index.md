---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ορίζει έγγραφα λογιστικού φύλλου."
type: docs
weight: 25
url: /el/java/com.groupdocs.conversion.filetypes/spreadsheetfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class SpreadsheetFileType extends FileType implements Serializable
```

Ορίζει έγγραφα Spreadsheet. Περιλαμβάνει τους παρακάτω τύπους αρχείων:
[Csv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Csv),
[Fods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Fods),
[Ods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ods),
[Ots](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ots),
[Tsv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Tsv),
[Xlam](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlam),
[Xls](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xls),
[Xlsb](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsb),
[Xlsm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsm),
[Xlsx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsx),
[Xlt](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlt),
[Xltm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltm),
[Xltx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltx).
Μάθετε περισσότερα για τις μορφές Spreadsheet [εδώ](../https://wiki.fileformat.com/spreadsheet).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SpreadsheetFileType()](#SpreadsheetFileType--) | Κατασκευαστής σειριοποίησης |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Xls](#Xls) | Το XLS αντιπροσωπεύει τη μορφή Excel Binary File Format. |
|
|  | [Xlsx](#Xlsx) | Το XLSX είναι μια γνωστή μορφή για έγγραφα Microsoft Excel που εισήχθη από τη Microsoft με την κυκλοφορία του Microsoft Office 2007. |
|
|  | [Xlsm](#Xlsm) | Το XLSM είναι ένας τύπος αρχείων Spreadsheet που υποστηρίζουν μακροεντολές. |
|
|  | [Xlsb](#Xlsb) | Η μορφή αρχείου XLSB καθορίζει το Excel Binary File Format, το οποίο είναι μια συλλογή εγγραφών και δομών που καθορίζουν το περιεχόμενο του βιβλίου εργασίας Excel. |
|
|  | [Ods](#Ods) | Τα αρχεία με την επέκταση ODS αντιπροσωπεύουν τη μορφή OpenDocument Spreadsheet Document, η οποία είναι επεξεργάσιμη από τον χρήστη. |
|
|  | [Ots](#Ots) | Ένα αρχείο με την επέκταση .ots είναι ένα αρχείο προτύπου OpenDocument Spreadsheet που δημιουργείται με το λογισμικό εφαρμογής Calc που περιλαμβάνεται στο Apache OpenOffice. |
|
|  | [Xltx](#Xltx) | Το αρχείο XLTX αντιπροσωπεύει το Microsoft Excel Template, το οποίο βασίζεται στις προδιαγραφές της μορφής αρχείου Office OpenXML. |
|
|  | [Xlt](#Xlt) | Τα αρχεία με την επέκταση .XLT είναι αρχεία προτύπων που δημιουργήθηκαν με το Microsoft Excel, το οποίο είναι μια εφαρμογή λογιστικού φύλλου που αποτελεί μέρος της σουίτας Microsoft Office. |
|
|  | [Xltm](#Xltm) | Η επέκταση αρχείου XLTM αντιπροσωπεύει αρχεία που δημιουργούνται από το Microsoft Excel ως αρχεία προτύπου με ενεργοποιημένες μακροεντολές. |
|
|  | [Tsv](#Tsv) | Μια μορφή αρχείου Tab-Separated Values (TSV) αντιπροσωπεύει δεδομένα χωρισμένα με καρτέλες σε απλό κείμενο. |
|
|  | [Xlam](#Xlam) | Το XLAM είναι ένα αρχείο πρόσθετου Macro-Enabled που χρησιμοποιείται για την προσθήκη νέων λειτουργιών στα λογιστικά φύλλα. |
|
|  | [Csv](#Csv) | Τα αρχεία με την επέκταση CSV (Comma Separated Values) αντιπροσωπεύουν αρχεία απλού κειμένου που περιέχουν εγγραφές δεδομένων με τιμές χωρισμένες με κόμμα. |
|
|  | [Fods](#Fods) | Ένα αρχείο με την επέκταση .fods είναι ένας τύπος μορφής εγγράφου OpenDocument Spreadsheet που αποθηκεύει δεδομένα σε σειρές και στήλες. |
|
|  | [Dif](#Dif) | Το DIF σημαίνει Data Interchange Format, το οποίο χρησιμοποιείται για την εισαγωγή/εξαγωγή δεδομένων λογιστικών φύλλων μεταξύ διαφορετικών εφαρμογών. |
|
|  | [Sxc](#Sxc) | Η μορφή αρχείου SXC (Sun XML Calc) ανήκει σε μια σουίτα γραφείου που ονομάζεται OpenOffice.org. |
|
|  | [Numbers](#Numbers) | Τα αρχεία με επέκταση .numbers ταξινομούνται ως τύπος αρχείου λογιστικού φύλλου, γι\u2019 αυτό είναι παρόμοια με τα αρχεία .xlsx· αλλά τα αρχεία Numbers δημιουργούνται με τη χρήση του λογισμικού Apple iWork Numbers. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### SpreadsheetFileType() {#SpreadsheetFileType--}
```
public SpreadsheetFileType()
```


Κατασκευαστής σειριοποίησης


### Xls {#Xls}
```
public static final SpreadsheetFileType Xls
```


Το XLS αντιπροσωπεύει τη μορφή αρχείου Excel Binary. Τέτοια αρχεία μπορούν να δημιουργηθούν από το Microsoft Excel καθώς και από άλλα παρόμοια προγράμματα λογιστικών φύλλων όπως το OpenOffice Calc ή το Apple Numbers.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/spreadsheet/xls).


### Xlsx {#Xlsx}
```
public static final SpreadsheetFileType Xlsx
```


Το XLSX είναι μια γνωστή μορφή για έγγραφα Microsoft Excel που εισήχθη από τη Microsoft με την κυκλοφορία του Microsoft Office 2007.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/spreadsheet/xlsx).


### Xlsm {#Xlsm}
```
public static final SpreadsheetFileType Xlsm
```


Το XLSM είναι ένας τύπος αρχείων Spreadsheet που υποστηρίζουν μακροεντολές.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/spreadsheet/xlsm).


### Xlsb {#Xlsb}
```
public static final SpreadsheetFileType Xlsb
```


Η μορφή αρχείου XLSB καθορίζει το Excel Binary File Format, το οποίο είναι μια συλλογή εγγραφών και δομών που καθορίζουν το περιεχόμενο του βιβλίου εργασίας Excel.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/spreadsheet/xlsb).


### Ods {#Ods}
```
public static final SpreadsheetFileType Ods
```


Τα αρχεία με επέκταση ODS αντιπροσωπεύουν τη μορφή εγγράφου OpenDocument Spreadsheet που μπορούν να επεξεργαστούν από το χρήστη. Τα δεδομένα αποθηκεύονται μέσα στο αρχείο ODF σε σειρές και στήλες.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/spreadsheet/ods).


### Ots {#Ots}
```
public static final SpreadsheetFileType Ots
```


Ένα αρχείο με επέκταση .ots είναι ένα πρότυπο αρχείου OpenDocument Spreadsheet που δημιουργείται με το λογισμικό εφαρμογής Calc που περιλαμβάνεται στο Apache OpenOffice. Το λογισμικό εφαρμογής Calc είναι παρόμοιο με το Excel που διατίθεται στο Microsoft Office.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/spreadsheet/ots).


### Xltx {#Xltx}
```
public static final SpreadsheetFileType Xltx
```


Το αρχείο XLTX αντιπροσωπεύει πρότυπο Microsoft Excel που βασίζεται στις προδιαγραφές μορφής αρχείου Office OpenXML. Χρησιμοποιείται για τη δημιουργία ενός τυπικού αρχείου προτύπου που μπορεί να χρησιμοποιηθεί για την παραγωγή αρχείων XLSX που εμφανίζουν τις ίδιες ρυθμίσεις όπως ορίζονται στο αρχείο XLTX.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/spreadsheet/xltx).


### Xlt {#Xlt}
```
public static final SpreadsheetFileType Xlt
```


Τα αρχεία με επέκταση .XLT είναι αρχεία προτύπου που δημιουργούνται με το Microsoft Excel, το οποίο είναι μια εφαρμογή λογιστικού φύλλου που αποτελεί μέρος της σουίτας Microsoft Office. Το Microsoft Office 97-2003 υποστήριζε τη δημιουργία νέων αρχείων XLT καθώς και το άνοιγμά τους.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/spreadsheet/xlt).


### Xltm {#Xltm}
```
public static final SpreadsheetFileType Xltm
```


Η επέκταση αρχείου XLTM αντιπροσωπεύει αρχεία που δημιουργούνται από το Microsoft Excel ως πρότυπα με ενεργοποιημένες μακροεντολές. Τα αρχεία XLTM είναι παρόμοια με τα XLTX σε δομή, εκτός από το ότι τα δεύτερα δεν υποστηρίζουν τη δημιουργία προτύπων με μακροεντολές.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/spreadsheet/xltm).


### Tsv {#Tsv}
```
public static final SpreadsheetFileType Tsv
```


Μια μορφή αρχείου Tab-Separated Values (TSV) αντιπροσωπεύει δεδομένα χωρισμένα με καρτέλες σε απλό κείμενο.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/spreadsheet/tsv).


### Xlam {#Xlam}
```
public static final SpreadsheetFileType Xlam
```


Το XLAM είναι ένα αρχείο πρόσθετου με ενεργοποιημένες μακροεντολές που χρησιμοποιείται για την προσθήκη νέων λειτουργιών στα λογιστικά φύλλα. Ένα πρόσθετο είναι ένα συμπληρωματικό πρόγραμμα που εκτελεί επιπλέον κώδικα και παρέχει επιπλέον λειτουργικότητα για τα λογιστικά φύλλα.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://docs.fileformat.com/spreadsheet/xlam/)


### Csv {#Csv}
```
public static final SpreadsheetFileType Csv
```


Τα αρχεία με την επέκταση CSV (Comma Separated Values) αντιπροσωπεύουν αρχεία απλού κειμένου που περιέχουν εγγραφές δεδομένων με τιμές χωρισμένες με κόμμα.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/spreadsheet/csv).


### Fods {#Fods}
```
public static final SpreadsheetFileType Fods
```


Ένα αρχείο με επέκταση .fods είναι ένας τύπος μορφής εγγράφου OpenDocument Spreadsheet που αποθηκεύει δεδομένα σε σειρές και στήλες. Η μορφή ορίζεται ως μέρος των προδιαγραφών ODF 1.2 που δημοσιεύονται και συντηρούνται από το OASIS. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/spreadsheet/fods).


### Dif {#Dif}
```
public static final SpreadsheetFileType Dif
```


Το DIF σημαίνει Data Interchange Format και χρησιμοποιείται για την εισαγωγή/εξαγωγή δεδομένων λογιστικών φύλλων μεταξύ διαφορετικών εφαρμογών. Αυτές περιλαμβάνουν το Microsoft Excel, το OpenOffice Calc, το StarCalc και πολλά άλλα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/spreadsheet/dif).


### Sxc {#Sxc}
```
public static final SpreadsheetFileType Sxc
```


Η μορφή αρχείου SXC (Sun XML Calc) ανήκει σε μια σουίτα γραφείου που ονομάζεται OpenOffice.org. Αυτή η μορφή εξυπηρετεί γενικά τις ανάγκες των χρηστών λογιστικών φύλλων, καθώς είναι μια μορφή αρχείου λογιστικού φύλλου βασισμένη σε XML. Η μορφή SXC υποστηρίζει τύπους, συναρτήσεις, μακροεντολές και διαγράμματα μαζί με το DataPilot. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/spreadsheet/sxc).


### Numbers {#Numbers}
```
public static final SpreadsheetFileType Numbers
```


Τα αρχεία με επέκταση .numbers ταξινομούνται ως τύπος αρχείου λογιστικού φύλλου, γι' αυτό είναι παρόμοια με τα αρχεία .xlsx· αλλά τα αρχεία Numbers δημιουργούνται με τη χρήση του λογισμικού λογιστικών φύλλων Apple iWork Numbers. Μάθετε περισσότερα για αυτόν τον τύπο αρχείου [εδώ](../https://docs.fileformat.com/spreadsheet/numbers).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Προετοιμάστηκαν προεπιλεγμένες επιλογές φόρτωσης για τον τύπο πηγαίου αρχείου


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Προετοιμάστηκαν προεπιλεγμένες επιλογές μετατροπής για τον τύπο αρχείου


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
