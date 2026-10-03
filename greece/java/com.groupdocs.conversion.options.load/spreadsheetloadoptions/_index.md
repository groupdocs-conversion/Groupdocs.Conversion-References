---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές φόρτωσης εγγράφων λογιστικού φύλλου."
type: docs
weight: 31
url: /el/java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable, [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable, IDocumentsContainerLoadOptions
```

Επιλογές φόρτωσης εγγράφων λογιστικού φύλλου.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Αρχικοποιεί μια νέα παρουσία της [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions) κλάσης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSheets()](#getSheets--) | Αποκτήστε το όνομα φύλλου για μετατροπή |
|
|  | [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | Ορίστε το όνομα φύλλου για μετατροπή |
|
|  | [getCultureInfo()](#getCultureInfo--) | Αποκτήστε τις πληροφορίες πολιτισμού του συστήματος τη στιγμή που το αρχείο φορτώνεται |
|
|  | [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | Ορίστε τις πληροφορίες πολιτισμού του συστήματος τη στιγμή που το αρχείο φορτώνεται |
|
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Προεπιλεγμένη γραμματοσειρά για έγγραφο λογιστικού φύλλου. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Προεπιλεγμένη γραμματοσειρά για έγγραφο λογιστικού φύλλου. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Αντικαταστήστε συγκεκριμένες γραμματοσειρές κατά τη μετατροπή εγγράφου λογιστικού φύλλου. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Αντικαταστήστε συγκεκριμένες γραμματοσειρές κατά τη μετατροπή εγγράφου λογιστικού φύλλου. |
|
|  | [getShowGridLines()](#getShowGridLines--) | Εμφανίστε τις γραμμές πλέγματος κατά τη μετατροπή αρχείων Excel. |
|
|  | [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | Εμφανίστε τις γραμμές πλέγματος κατά τη μετατροπή αρχείων Excel. |
|
|  | [getShowHiddenSheets()](#getShowHiddenSheets--) | Εμφανίστε τα κρυφά φύλλα κατά τη μετατροπή αρχείων Excel. |
|
|  | [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | Εμφανίστε τα κρυφά φύλλα κατά τη μετατροπή αρχείων Excel. |
|
|  | [getOnePagePerSheet()](#getOnePagePerSheet--) | Εάν το OnePagePerSheet είναι αληθές, το περιεχόμενο του φύλλου θα μετατραπεί σε μία σελίδα στο έγγραφο PDF. |
|
|  | [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | Εάν το OnePagePerSheet είναι αληθές, το περιεχόμενο του φύλλου θα μετατραπεί σε μία σελίδα στο έγγραφο PDF. |
|
|  | [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | Αποκτά την ιδιότητα AllColumnsInOnePagePerSheet |
|
|  | [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | Ορίζει την ιδιότητα AllColumnsInOnePagePerSheet |
|
|  | [getOptimizePdfSize()](#getOptimizePdfSize--) | Εάν είναι True και γίνεται μετατροπή σε PDF, η μετατροπή βελτιστοποιείται για καλύτερο μέγεθος αρχείου σε σχέση με την ποιότητα εκτύπωσης. |
|
|  | [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | Εάν είναι True και γίνεται μετατροπή σε PDF, η μετατροπή βελτιστοποιείται για καλύτερο μέγεθος αρχείου σε σχέση με την ποιότητα εκτύπωσης. |
|
|  | [getConvertRange()](#getConvertRange--) | Μετατρέψτε συγκεκριμένο εύρος κατά τη μετατροπή σε μορφή διαφορετική από λογιστικό φύλλο. |
|
|  | [setConvertRange(String value)](#setConvertRange-java.lang.String-) | Μετατρέψτε συγκεκριμένο εύρος κατά τη μετατροπή σε μορφή διαφορετική από λογιστικό φύλλο. |
|
|  | [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | Παραλείπει κενές γραμμές και στήλες κατά τη μετατροπή. |
|
|  | [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | Παραλείπει κενές γραμμές και στήλες κατά τη μετατροπή. |
|
|  | [getPassword()](#getPassword--) | Ορίστε κωδικό πρόσβασης για την αποπροστασία του προστατευμένου εγγράφου. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ορίστε κωδικό πρόσβασης για την αποπροστασία του προστατευμένου εγγράφου. |
|
|  | [getHideComments()](#getHideComments--) | Απόκρυψη σχολίων. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Απόκρυψη σχολίων. |
|
|  | [isCheckExcelRestriction()](#isCheckExcelRestriction--) | Καθορίζει αν ελέγχεται ο περιορισμός του αρχείου Excel όταν ο χρήστης τροποποιεί αντικείμενα σχετιζόμενα με κελιά. |
|
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
|  | [getSheetIndexes()](#getSheetIndexes--) | Αποκτά τη λίστα των δεικτών φύλλων για μετατροπή. |
|
|  | [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | Ορίζει τη λίστα των δεικτών φύλλων για μετατροπή. |
|
|  | [isAutoFitRows()](#isAutoFitRows--) | Αυτοπροσαρμογή όλων των γραμμών κατά τη μετατροπή |
|
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
|  | [getResetFontFolders()](#getResetFontFolders--) | Επαναφορά φακέλων γραμματοσειρών πριν τη φόρτωση του εγγράφου |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [deepClone()](#deepClone--) | Κλωνοποιεί την τρέχουσα παρουσία. |
|
|  | [getRowsPerPage()](#getRowsPerPage--) | Διαιρέστε ένα φύλλο εργασίας σε σελίδες ανά γραμμές |
|
|  | [setRowsPerPage(int rowsPerPage)](#setRowsPerPage-int-) | Διαιρέστε ένα φύλλο εργασίας σε σελίδες ανά γραμμές |
|
|  | [getColumnsPerPage()](#getColumnsPerPage--) | Διαιρέστε ένα φύλλο εργασίας σε σελίδες ανά στήλες |
|
|  | [setColumnsPerPage(int columnsPerPage)](#setColumnsPerPage-int-) | Διαιρέστε ένα φύλλο εργασίας σε σελίδες ανά στήλες |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Αρχικοποιεί μια νέα παρουσία της [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions) κλάσης.


### getSheets() {#getSheets--}
```
public List<String> getSheets()
```


Αποκτήστε το όνομα φύλλου για μετατροπή


**Returns:**
java.util.List<java.lang.String>
### setSheets(List<String> sheets) {#setSheets-java.util.List-java.lang.String--}
```
public void setSheets(List<String> sheets)
```


Ορίστε το όνομα φύλλου για μετατροπή


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| φύλλα | java.util.List<java.lang.String> |  |

### getCultureInfo() {#getCultureInfo--}
```
public System.Globalization.CultureInfo getCultureInfo()
```


Αποκτήστε τις πληροφορίες πολιτισμού του συστήματος τη στιγμή που το αρχείο φορτώνεται


**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


Ορίστε τις πληροφορίες πολιτισμού του συστήματος τη στιγμή που το αρχείο φορτώνεται


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| cultureInfo | com.aspose.ms.System.Globalization.CultureInfo |  |

### getFormat() {#getFormat--}
```
public final SpreadsheetFileType getFormat()
```


Τύπος αρχείου εισαγόμενου εγγράφου


**Returns:**
[SpreadsheetFileType](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Προεπιλεγμένη γραμματοσειρά για το έγγραφο λογιστικού φύλλου. Η παρακάτω γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Προεπιλεγμένη γραμματοσειρά για το έγγραφο λογιστικού φύλλου. Η παρακάτω γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Αντικαταστήστε συγκεκριμένες γραμματοσειρές κατά τη μετατροπή εγγράφου λογιστικού φύλλου.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Αντικαταστήστε συγκεκριμένες γραμματοσειρές κατά τη μετατροπή εγγράφου λογιστικού φύλλου.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


Εμφανίστε τις γραμμές πλέγματος κατά τη μετατροπή αρχείων Excel.


**Returns:**
boolean
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


Εμφανίστε τις γραμμές πλέγματος κατά τη μετατροπή αρχείων Excel.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


Εμφανίστε τα κρυφά φύλλα κατά τη μετατροπή αρχείων Excel.


**Returns:**
boolean
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


Εμφανίστε τα κρυφά φύλλα κατά τη μετατροπή αρχείων Excel.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


Εάν το OnePagePerSheet είναι true, το περιεχόμενο του φύλλου θα μετατραπεί σε μία σελίδα στο έγγραφο PDF. Η προεπιλεγμένη τιμή είναι false.


**Returns:**
boolean
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


Εάν το OnePagePerSheet είναι true, το περιεχόμενο του φύλλου θα μετατραπεί σε μία σελίδα στο έγγραφο PDF. Η προεπιλεγμένη τιμή είναι false.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


Αποκτά την ιδιότητα AllColumnsInOnePagePerSheet


**Returns:**
boolean - true εάν προσαρμόζει όλες τις στήλες σε μία σελίδα

### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


Ορίζει την ιδιότητα AllColumnsInOnePagePerSheet


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | allColumnsInOnePagePerSheet | boolean | AllColumnsInOnePagePerSheet ιδιότητα |
|

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


Εάν είναι True και γίνεται μετατροπή σε PDF, η μετατροπή βελτιστοποιείται για καλύτερο μέγεθος αρχείου σε σχέση με την ποιότητα εκτύπωσης.


**Returns:**
boolean
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


Εάν είναι True και γίνεται μετατροπή σε PDF, η μετατροπή βελτιστοποιείται για καλύτερο μέγεθος αρχείου σε σχέση με την ποιότητα εκτύπωσης.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


Μετατρέψτε συγκεκριμένο εύρος κατά τη μετατροπή σε μορφή διαφορετική από το λογιστικό φύλλο. Παράδειγμα: "D1:F8".


**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


Μετατρέψτε συγκεκριμένο εύρος κατά τη μετατροπή σε μορφή διαφορετική από το λογιστικό φύλλο. Παράδειγμα: "D1:F8".


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


Παραλείπει κενές γραμμές και στήλες κατά τη μετατροπή. Η προεπιλογή είναι True.


**Returns:**
boolean
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


Παραλείπει κενές γραμμές και στήλες κατά τη μετατροπή. Η προεπιλογή είναι True.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ορίστε κωδικό πρόσβασης για την αποπροστασία του προστατευμένου εγγράφου.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ορίστε κωδικό πρόσβασης για την αποπροστασία του προστατευμένου εγγράφου.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Απόκρυψη σχολίων.


**Returns:**
boolean
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Απόκρυψη σχολίων.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


Καθορίζει εάν ελέγχεται ο περιορισμός του αρχείου Excel όταν ο χρήστης τροποποιεί αντικείμενα σχετιζόμενα με κελιά. Για παράδειγμα, το Excel δεν επιτρέπει την εισαγωγή τιμής συμβολοσειράς μεγαλύτερης από 32K. Όταν εισάγετε μια τιμή μεγαλύτερη από 32K, εάν αυτή η ιδιότητα είναι true, θα λάβετε μια Exception. Εάν αυτή η ιδιότητα είναι false, θα αποδεχθούμε την εισαγόμενη τιμή συμβολοσειράς ως τιμή του κελιού, ώστε αργότερα να μπορείτε να εξάγετε την πλήρη τιμή συμβολοσειράς για άλλες μορφές αρχείων όπως CSV. Ωστόσο, εάν έχετε ορίσει τέτοια τιμή που είναι μη έγκυρη για τη μορφή αρχείου Excel, δεν πρέπει να αποθηκεύσετε το βιβλίο εργασίας ως μορφή αρχείου Excel αργότερα. Διαφορετικά, μπορεί να προκύψει απροσδόκητο σφάλμα στο παραγόμενο αρχείο Excel.


**Returns:**
boolean - σημαία ελέγχου περιορισμού

### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| checkExcelRestriction | boolean |  |

### getSheetIndexes() {#getSheetIndexes--}
```
public List<Integer> getSheetIndexes()
```


Αποκτά τη λίστα των δεικτών φύλλων για μετατροπή.


**Returns:**
java.util.List<java.lang.Integer>
### setSheetIndexes(List<Integer> sheetIndexes) {#setSheetIndexes-java.util.List-java.lang.Integer--}
```
public void setSheetIndexes(List<Integer> sheetIndexes)
```


Ορίζει τη λίστα των δεικτών φύλλων προς μετατροπή. Οι δείκτες πρέπει να είναι μηδενικής βάσης


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sheetIndexes | java.util.List<java.lang.Integer> |  |

### isAutoFitRows() {#isAutoFitRows--}
```
public boolean isAutoFitRows()
```


Αυτοπροσαρμογή όλων των γραμμών κατά τη μετατροπή


**Returns:**
boolean
### setAutoFitRows(boolean autoFitRows) {#setAutoFitRows-boolean-}
```
public void setAutoFitRows(boolean autoFitRows)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| autoFitRows | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Επαναφορά φακέλων γραμματοσειρών πριν τη φόρτωση του εγγράφου


**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| resetFontFolders | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Κλωνοποιεί την τρέχουσα παρουσία.


**Returns:**
java.lang.Object -
### getRowsPerPage() {#getRowsPerPage--}
```
public int getRowsPerPage()
```


Διαχωρίζει ένα φύλλο εργασίας σε σελίδες ανά γραμμές. Η προεπιλογή είναι 0, χωρίς σελιδοποίηση.


**Returns:**
int
### setRowsPerPage(int rowsPerPage) {#setRowsPerPage-int-}
```
public void setRowsPerPage(int rowsPerPage)
```


Διαχωρίζει ένα φύλλο εργασίας σε σελίδες ανά γραμμές. Η προεπιλογή είναι 0, χωρίς σελιδοποίηση.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| rowsPerPage | int |  |

### getColumnsPerPage() {#getColumnsPerPage--}
```
public int getColumnsPerPage()
```


Διαχωρίζει ένα φύλλο εργασίας σε σελίδες ανά στήλες. Η προεπιλογή είναι 0, χωρίς σελιδοποίηση.


**Returns:**
int
### setColumnsPerPage(int columnsPerPage) {#setColumnsPerPage-int-}
```
public void setColumnsPerPage(int columnsPerPage)
```


Διαχωρίζει ένα φύλλο εργασίας σε σελίδες ανά στήλες. Η προεπιλογή είναι 0, χωρίς σελιδοποίηση.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| columnsPerPage | int |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Λαμβάνει επιλογή για τον έλεγχο εάν το ίδιο το δοχείο των εγγράφων πρέπει να μετατραπεί


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Επιλογή για έλεγχο του αν τα ιδιόκτητα έγγραφα στο δοχείο εγγράφων πρέπει να μετατραπούν


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Επιλογή για έλεγχο του πόσων επιπέδων σε βάθος θα γίνει η μετατροπή


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| depth | int |  |

