---
title: "PdfLoadOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές φόρτωσης εγγράφων PDF."
type: docs
weight: 27
url: /el/java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public final class PdfLoadOptions extends LoadOptions implements Serializable, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Επιλογές φόρτωσης εγγράφων PDF.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PdfLoadOptions()](#PdfLoadOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Αφαίρεση ενσωματωμένων αρχείων. |
|
|  | [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Αφαίρεση ενσωματωμένων αρχείων. |
|
|  | [getPassword()](#getPassword--) | Ορίστε κωδικό πρόσβασης για την αποπροστασία του προστατευμένου εγγράφου. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ορίστε κωδικό πρόσβασης για την αποπροστασία του προστατευμένου εγγράφου. |
|
|  | [getDefaultFont()](#getDefaultFont--) | Προεπιλεγμένη γραμματοσειρά για έγγραφο Pdf. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Προεπιλεγμένη γραμματοσειρά για έγγραφο Pdf. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Αντικατάσταση συγκεκριμένων γραμματοσειρών κατά τη μετατροπή εγγράφου Pdf. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Αντικατάσταση συγκεκριμένων γραμματοσειρών κατά τη μετατροπή εγγράφου Pdf. |
|
|  | [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Απόκρυψη σχολίων σε έγγραφα Pdf. |
|
|  | [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Απόκρυψη σχολίων σε έγγραφα Pdf. |
|
|  | [getFlattenAllFields()](#getFlattenAllFields--) | Ισοπέδωση όλων των πεδίων της φόρμας PDF. |
|
|  | [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | Ισοπέδωση όλων των πεδίων της φόρμας PDF. |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Επαναφορά φακέλων γραμματοσειρών πριν τη φόρτωση του εγγράφου. |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Ενεργοποίηση ή απενεργοποίηση της δημιουργίας αρίθμησης σελίδων στο μετατρεπόμενο έγγραφο. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [isRemoveJavascript()](#isRemoveJavascript--) | Λαμβάνει τη σημαία Remove JavaScript. |
|
|  | [setRemoveJavascript(boolean removeJavascript)](#setRemoveJavascript-boolean-) | Ορίζει τη σημαία Remove JavaScript. |
|
|  | [isConvertOwner()](#isConvertOwner--) | Καθορίζει εάν το έγγραφο ιδιοκτήτη πρέπει να μετατραπεί. |
|
|  | [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) | Καθορίζει εάν το έγγραφο ιδιοκτήτη πρέπει να μετατραπεί. |
|
|  | [isConvertOwned()](#isConvertOwned--) | Καθορίζει εάν τα ιδιόκτητα έγγραφα πρέπει να μετατραπούν. |
|
|  | [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) | Καθορίζει εάν τα ιδιόκτητα έγγραφα πρέπει να μετατραπούν. |
|
|  | [getDepth()](#getDepth--) | Μέγιστο βάθος για την επεξεργασία ιδιόκτητων εγγράφων. |
|
|  | [setDepth(int depth)](#setDepth-int-) | Μέγιστο βάθος για την επεξεργασία ιδιόκτητων εγγράφων. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions).


### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


Τύπος αρχείου εισαγόμενου εγγράφου


**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


Αφαίρεση ενσωματωμένων αρχείων.


**Returns:**
boolean
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


Αφαίρεση ενσωματωμένων αρχείων.


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

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Προεπιλεγμένη γραμματοσειρά για έγγραφο Pdf.
Η παρακάτω γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Προεπιλεγμένη γραμματοσειρά για έγγραφο Pdf.
Η παρακάτω γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Αντικατάσταση συγκεκριμένων γραμματοσειρών κατά τη μετατροπή εγγράφου Pdf.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Αντικατάσταση συγκεκριμένων γραμματοσειρών κατά τη μετατροπή εγγράφου Pdf.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getHidePdfAnnotations() {#getHidePdfAnnotations--}
```
public final boolean getHidePdfAnnotations()
```


Απόκρυψη σχολίων σε έγγραφα Pdf.


**Returns:**
boolean
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


Απόκρυψη σχολίων σε έγγραφα Pdf.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


Ισοπέδωση όλων των πεδίων της φόρμας PDF.


**Returns:**
boolean
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


Ισοπέδωση όλων των πεδίων της φόρμας PDF.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Επαναφορά φακέλων γραμματοσειρών πριν τη φόρτωση του εγγράφου.


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

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Ενεργοποίηση ή απενεργοποίηση της δημιουργίας αρίθμησης σελίδων στο μετατρεπόμενο έγγραφο. Προεπιλογή: false.


**Returns:**
boolean
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| isPageNumbering | boolean |  |

### isRemoveJavascript() {#isRemoveJavascript--}
```
public boolean isRemoveJavascript()
```


Λαμβάνει τη σημαία Remove JavaScript.


**Returns:**
boolean
### setRemoveJavascript(boolean removeJavascript) {#setRemoveJavascript-boolean-}
```
public void setRemoveJavascript(boolean removeJavascript)
```


Ορίζει τη σημαία Remove JavaScript.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| removeJavascript | boolean |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Καθορίζει εάν το έγγραφο ιδιοκτήτη πρέπει να μετατραπεί.

Η προεπιλογή είναι
true
.


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```


Καθορίζει εάν το έγγραφο ιδιοκτήτη πρέπει να μετατραπεί.

Η προεπιλογή είναι
true
.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Καθορίζει εάν τα ιδιόκτητα έγγραφα πρέπει να μετατραπούν.

Η προεπιλογή είναι
ψευδής
.


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```


Καθορίζει εάν τα ιδιόκτητα έγγραφα πρέπει να μετατραπούν.

Η προεπιλογή είναι
ψευδής
.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Μέγιστο βάθος για την επεξεργασία ιδιόκτητων εγγράφων.

Η προεπιλογή είναι
2
.


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```


Μέγιστο βάθος για την επεξεργασία ιδιόκτητων εγγράφων.

Η προεπιλογή είναι
2
.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| depth | int |  |

