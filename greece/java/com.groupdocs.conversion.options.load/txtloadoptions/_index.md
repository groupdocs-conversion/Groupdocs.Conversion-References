---
title: "TxtLoadOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές φόρτωσης εγγράφων Txt."
type: docs
weight: 34
url: /el/java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

Επιλογές φόρτωσης εγγράφων Txt.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [TxtLoadOptions()](#TxtLoadOptions--) | Αρχικοποιεί νέα παρουσία της κλάσης [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | Επιτρέπει τον καθορισμό του πώς αναγνωρίζονται τα στοιχεία αριθμημένης λίστας όταν μετατρέπεται ένα έγγραφο απλού κειμένου. |
|
|  | [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | Επιτρέπει τον καθορισμό του πώς αναγνωρίζονται τα στοιχεία αριθμημένης λίστας όταν μετατρέπεται ένα έγγραφο απλού κειμένου. |
|
|  | [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης τελικού διαστήματος. |
|
|  | [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης τελικού διαστήματος. |
|
|  | [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης αρχικού διαστήματος. |
|
|  | [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης αρχικού διαστήματος. |
|
|  | [getEncoding()](#getEncoding--) | Λαμβάνει ή ορίζει την κωδικοποίηση που θα χρησιμοποιηθεί κατά τη φόρτωση του εγγράφου Txt. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Λαμβάνει ή ορίζει την κωδικοποίηση που θα χρησιμοποιηθεί κατά τη φόρτωση του εγγράφου Txt. |
|
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


Αρχικοποιεί νέα παρουσία της κλάσης [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions).


### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


Τύπος αρχείου εισαγόμενου εγγράφου


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


Επιτρέπει τον καθορισμό του πώς αναγνωρίζονται τα στοιχεία αριθμημένης λίστας όταν μετατρέπεται ένα έγγραφο απλού κειμένου.
Η προεπιλεγμένη τιμή είναι true.

<br />

*** ** * ** ***

Εάν αυτή η επιλογή οριστεί σε false, ο αλγόριθμος αναγνώρισης λιστών εντοπίζει παραγράφους λιστών, όταν οι αριθμοί λίστας τελειώνουν με
είτε τελεία, δεξιό αγκύλη ή σύμβολα κουκίδας (όπως "\u2022", "*", "-" ή "o").

Εάν αυτή η επιλογή οριστεί σε true, τα κενά χρησιμοποιούνται επίσης ως διαχωριστικά αριθμών λίστας:
Ο αλγόριθμος αναγνώρισης λίστας για αραβική μορφή αρίθμησης (1., 1.1.2.) χρησιμοποιεί τόσο τα κενά όσο και το σύμβολο τελείας (".").

<br />



**Returns:**
boolean
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


Επιτρέπει τον καθορισμό του πώς αναγνωρίζονται τα στοιχεία αριθμημένης λίστας όταν μετατρέπεται ένα έγγραφο απλού κειμένου.
Η προεπιλεγμένη τιμή είναι true.

<br />

*** ** * ** ***

Εάν αυτή η επιλογή οριστεί σε false, ο αλγόριθμος αναγνώρισης λιστών εντοπίζει παραγράφους λιστών, όταν οι αριθμοί λίστας τελειώνουν με
είτε τελεία, δεξιό αγκύλη ή σύμβολα κουκίδας (όπως "\u2022", "*", "-" ή "o").

Εάν αυτή η επιλογή οριστεί σε true, τα κενά χρησιμοποιούνται επίσης ως διαχωριστικά αριθμών λίστας:
Ο αλγόριθμος αναγνώρισης λίστας για αραβική μορφή αρίθμησης (1., 1.1.2.) χρησιμοποιεί τόσο τα κενά όσο και το σύμβολο τελείας (".").

<br />



**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης τελικού διαστήματος.
Η προεπιλεγμένη τιμή είναι [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης τελικού διαστήματος.
Η προεπιλεγμένη τιμή είναι [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης αρχικού διαστήματος.
Η προεπιλεγμένη τιμή είναι [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης αρχικού διαστήματος.
Η προεπιλεγμένη τιμή είναι [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Λαμβάνει ή ορίζει την κωδικοποίηση που θα χρησιμοποιηθεί κατά τη φόρτωση του εγγράφου Txt. Μπορεί να είναι null. Η προεπιλεγμένη τιμή είναι null.


**Returns:**
java.nio.charset.Charset
### getEncodingInternal() {#getEncodingInternal--}
```
public System.Text.Encoding getEncodingInternal()
```




**Returns:**
com.aspose.ms.System.Text.Encoding
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Λαμβάνει ή ορίζει την κωδικοποίηση που θα χρησιμοποιηθεί κατά τη φόρτωση του εγγράφου Txt. Μπορεί να είναι null. Η προεπιλεγμένη τιμή είναι null.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.nio.charset.Charset |  |

