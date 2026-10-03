---
title: "PdfFormattingOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ορίζει τις επιλογές μορφοποίησης Pdf."
type: docs
weight: 28
url: /el/java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

Ορίζει τις επιλογές μορφοποίησης Pdf.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getCenterWindow()](#getCenterWindow--) | Καθορίζει εάν η θέση του παραθύρου του εγγράφου θα κεντραριστεί στην οθόνη. |
|
|  | [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Καθορίζει εάν η θέση του παραθύρου του εγγράφου θα κεντραριστεί στην οθόνη. |
|
|  | [getDirection()](#getDirection--) | Ορίζει τη σειρά ανάγνωσης του κειμένου: L2R (από αριστερά προς δεξιά) ή R2L (από δεξιά προς αριστερά). |
|
|  | [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | Ορίζει τη σειρά ανάγνωσης του κειμένου: L2R (από αριστερά προς δεξιά) ή R2L (από δεξιά προς αριστερά). |
|
|  | [getDisplayDocTitle()](#getDisplayDocTitle--) | Καθορίζει εάν η γραμμή τίτλου του παραθύρου του εγγράφου πρέπει να εμφανίζει τον τίτλο του εγγράφου. |
|
|  | [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | Καθορίζει εάν η γραμμή τίτλου του παραθύρου του εγγράφου πρέπει να εμφανίζει τον τίτλο του εγγράφου. |
|
|  | [getFitWindow()](#getFitWindow--) | Καθορίζει εάν το παράθυρο του εγγράφου πρέπει να αλλάξει μέγεθος ώστε να ταιριάζει στην πρώτη εμφανιζόμενη σελίδα. |
|
|  | [setFitWindow(boolean value)](#setFitWindow-boolean-) | Καθορίζει εάν το παράθυρο του εγγράφου πρέπει να αλλάξει μέγεθος ώστε να ταιριάζει στην πρώτη εμφανιζόμενη σελίδα. |
|
|  | [getHideMenuBar()](#getHideMenuBar--) | Καθορίζει εάν η γραμμή μενού πρέπει να κρύβεται όταν το έγγραφο είναι ενεργό. |
|
|  | [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | Καθορίζει εάν η γραμμή μενού πρέπει να κρύβεται όταν το έγγραφο είναι ενεργό. |
|
|  | [getHideToolBar()](#getHideToolBar--) | Καθορίζει εάν η γραμμή εργαλείων πρέπει να κρύβεται όταν το έγγραφο είναι ενεργό. |
|
|  | [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Καθορίζει εάν η γραμμή εργαλείων πρέπει να κρύβεται όταν το έγγραφο είναι ενεργό. |
|
|  | [getHideWindowUI()](#getHideWindowUI--) | Καθορίζει εάν τα στοιχεία της διεπαφής χρήστη πρέπει να κρύβονται όταν το έγγραφο είναι ενεργό. |
|
|  | [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Καθορίζει εάν τα στοιχεία της διεπαφής χρήστη πρέπει να κρύβονται όταν το έγγραφο είναι ενεργό. |
|
|  | [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Ορίζει τη λειτουργία σελίδας, καθορίζοντας πώς θα εμφανίζεται το έγγραφο κατά την έξοδο από τη λειτουργία πλήρους οθόνης. |
|
|  | [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Ορίζει τη λειτουργία σελίδας, καθορίζοντας πώς θα εμφανίζεται το έγγραφο κατά την έξοδο από τη λειτουργία πλήρους οθόνης. |
|
|  | [getPageLayout()](#getPageLayout--) | Ορίζει τη διάταξη σελίδας που θα χρησιμοποιηθεί όταν ανοίξει το έγγραφο. |
|
|  | [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | Ορίζει τη διάταξη σελίδας που θα χρησιμοποιηθεί όταν ανοίξει το έγγραφο. |
|
|  | [getPageMode()](#getPageMode--) | Ορίζει τη λειτουργία σελίδας, καθορίζοντας πώς θα εμφανίζεται το έγγραφο όταν ανοίξει. |
|
|  | [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Ορίζει τη λειτουργία σελίδας, καθορίζοντας πώς θα εμφανίζεται το έγγραφο όταν ανοίξει. |
|
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


Καθορίζει εάν η θέση του παραθύρου του εγγράφου θα κεντραριστεί στην οθόνη. Προεπιλογή: false.


**Returns:**
boolean
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


Καθορίζει εάν η θέση του παραθύρου του εγγράφου θα κεντραριστεί στην οθόνη. Προεπιλογή: false.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


Ορίζει τη σειρά ανάγνωσης του κειμένου: L2R (από αριστερά προς δεξιά) ή R2L (από δεξιά προς αριστερά). Προεπιλογή: L2R.


**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


Ορίζει τη σειρά ανάγνωσης του κειμένου: L2R (από αριστερά προς δεξιά) ή R2L (από δεξιά προς αριστερά). Προεπιλογή: L2R.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


Καθορίζει εάν η γραμμή τίτλου του παραθύρου του εγγράφου πρέπει να εμφανίζει τον τίτλο του εγγράφου. Προεπιλογή: false.


**Returns:**
boolean
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


Καθορίζει εάν η γραμμή τίτλου του παραθύρου του εγγράφου πρέπει να εμφανίζει τον τίτλο του εγγράφου. Προεπιλογή: false.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


Καθορίζει εάν το παράθυρο του εγγράφου πρέπει να αλλάξει μέγεθος ώστε να ταιριάζει στην πρώτη εμφανιζόμενη σελίδα. Προεπιλογή: false.


**Returns:**
boolean
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


Καθορίζει εάν το παράθυρο του εγγράφου πρέπει να αλλάξει μέγεθος ώστε να ταιριάζει στην πρώτη εμφανιζόμενη σελίδα. Προεπιλογή: false.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


Καθορίζει εάν η γραμμή μενού πρέπει να κρύβεται όταν το έγγραφο είναι ενεργό. Προεπιλογή: false.


**Returns:**
boolean
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


Καθορίζει εάν η γραμμή μενού πρέπει να κρύβεται όταν το έγγραφο είναι ενεργό. Προεπιλογή: false.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


Καθορίζει εάν η γραμμή εργαλείων πρέπει να κρύβεται όταν το έγγραφο είναι ενεργό. Προεπιλογή: false.


**Returns:**
boolean
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


Καθορίζει εάν η γραμμή εργαλείων πρέπει να κρύβεται όταν το έγγραφο είναι ενεργό. Προεπιλογή: false.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


Καθορίζει εάν τα στοιχεία της διεπαφής χρήστη πρέπει να κρύβονται όταν το έγγραφο είναι ενεργό. Προεπιλογή: false.


**Returns:**
boolean
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


Καθορίζει εάν τα στοιχεία της διεπαφής χρήστη πρέπει να κρύβονται όταν το έγγραφο είναι ενεργό. Προεπιλογή: false.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


Ορίζει τη λειτουργία σελίδας, καθορίζοντας πώς θα εμφανίζεται το έγγραφο κατά την έξοδο από τη λειτουργία πλήρους οθόνης.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


Ορίζει τη λειτουργία σελίδας, καθορίζοντας πώς θα εμφανίζεται το έγγραφο κατά την έξοδο από τη λειτουργία πλήρους οθόνης.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


Ορίζει τη διάταξη σελίδας που θα χρησιμοποιηθεί όταν ανοίξει το έγγραφο.


**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


Ορίζει τη διάταξη σελίδας που θα χρησιμοποιηθεί όταν ανοίξει το έγγραφο.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


Ορίζει τη λειτουργία σελίδας, καθορίζοντας πώς θα εμφανίζεται το έγγραφο όταν ανοίξει.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


Ορίζει τη λειτουργία σελίδας, καθορίζοντας πώς θα εμφανίζεται το έγγραφο όταν ανοίξει.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

