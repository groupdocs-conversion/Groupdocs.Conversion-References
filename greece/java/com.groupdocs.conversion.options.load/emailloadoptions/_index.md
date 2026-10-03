---
title: "EmailLoadOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές φόρτωσης εγγράφων email."
type: docs
weight: 18
url: /el/java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Επιλογές φόρτωσης εγγράφων email.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [EmailLoadOptions()](#EmailLoadOptions--) | Αρχικοποιεί μια νέα παρουσία της [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) κλάσης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDisplayHeader()](#getDisplayHeader--) | Επιλογή για εμφάνιση ή απόκρυψη της κεφαλίδας του email. |
|
|  | [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | Επιλογή για εμφάνιση ή απόκρυψη της κεφαλίδας του email. |
|
|  | [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "from". |
|
|  | [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "from". |
|
|  | [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "to". |
|
|  | [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "to". |
|
|  | [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "Cc". |
|
|  | [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "Cc". |
|
|  | [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "Bcc". |
|
|  | [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "Bcc". |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | Λαμβάνει ή ορίζει τη διαφορά ώρας (UTC) για τις ημερομηνίες των μηνυμάτων. |
|
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Χρόνος λήξης για τη φόρτωση εξωτερικών πόρων |
|
|  | [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | Χρόνος λήξης για τη φόρτωση εξωτερικών πόρων (setter) |
|
|  | [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | Λαμβάνει ή ορίζει τη διαφορά ώρας (UTC) για τις ημερομηνίες των μηνυμάτων. |
|
|  | [deepClone()](#deepClone--) | Κλωνοποιεί την τρέχουσα παρουσία. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | Λαμβάνει τη χαρτογράφηση μεταξύ του μηνύματος email και της αναπαράστασης κειμένου πεδίου |
|
|  | [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | Ορίζει τη χαρτογράφηση μεταξύ του μηνύματος email και της αναπαράστασης κειμένου πεδίου |
|
|  | [isPreserveOriginalDate()](#isPreserveOriginalDate--) | Ορίζει αν χρειάζεται να διατηρηθεί η αρχική συμβολοσειρά κεφαλίδας ημερομηνίας στο μήνυμα email κατά την αποθήκευση ή όχι (Προεπιλεγμένη τιμή είναι true) |
|
|  | [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | Ορίζει αν χρειάζεται να διατηρηθεί η αρχική συμβολοσειρά κεφαλίδας ημερομηνίας στο μήνυμα email κατά την αποθήκευση ή όχι |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
|  | [isDisplayAttachments()](#isDisplayAttachments--) | Λαμβάνει την επιλογή για εμφάνιση ή απόκρυψη συνημμένων στην κεφαλίδα. |
|
|  | [setDisplayAttachments(boolean displayAttachments)](#setDisplayAttachments-boolean-) | Ορίζει την επιλογή για εμφάνιση ή απόκρυψη συνημμένων στην κεφαλίδα. |
|
|  | [isDisplaySubject()](#isDisplaySubject--) | Λαμβάνει την επιλογή για εμφάνιση ή απόκρυψη του θέματος στην κεφαλίδα. |
|
|  | [setDisplaySubject(boolean displaySubject)](#setDisplaySubject-boolean-) | Ορίζει την επιλογή για εμφάνιση ή απόκρυψη του θέματος στην κεφαλίδα |
|
|  | [isDisplaySent()](#isDisplaySent--) | Λαμβάνει την επιλογή για εμφάνιση ή απόκρυψη της ημερομηνίας/ώρας αποστολής στην κεφαλίδα. |
|
|  | [setDisplaySent(boolean displaySent)](#setDisplaySent-boolean-) | Ορίζει την επιλογή για εμφάνιση ή απόκρυψη της ημερομηνίας/ώρας αποστολής στην κεφαλίδα. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | Παραλείπει τη φόρτωση πόρων http εάν true |
|
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) |  |
### EmailLoadOptions() {#EmailLoadOptions--}
```
public EmailLoadOptions()
```


Αρχικοποιεί μια νέα παρουσία της [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) κλάσης.


### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


Τύπος αρχείου εισαγόμενου εγγράφου


**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


Επιλογή για εμφάνιση ή απόκρυψη της κεφαλίδας email. Προεπιλογή: true.


**Returns:**
boolean
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


Επιλογή για εμφάνιση ή απόκρυψη της κεφαλίδας email. Προεπιλογή: true.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "from". Προεπιλογή: true.


**Returns:**
boolean
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "from". Προεπιλογή: true.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "to". Προεπιλογή: true.


**Returns:**
boolean
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "to". Προεπιλογή: true.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "Cc". Προεπιλογή: false.


**Returns:**
boolean
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "Cc". Προεπιλογή: false.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "Bcc". Προεπιλογή: false.


**Returns:**
boolean
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


Επιλογή για εμφάνιση ή απόκρυψη της διεύθυνσης email "Bcc". Προεπιλογή: false.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final Double getTimeZoneOffset()
```


Λαμβάνει ή ορίζει την απόκλιση του Συντονισμένου Παγκόσμιου Χρόνου (UTC) για τις ημερομηνίες των μηνυμάτων. Αυτή η ιδιότητα ορίζει τη διαφορά ζώνης ώρας μεταξύ της τοπικής ώρας και του UTC.


**Returns:**
java.lang.Double
### getTimeZoneOffsetInternal() {#getTimeZoneOffsetInternal--}
```
public System.TimeSpan getTimeZoneOffsetInternal()
```




**Returns:**
com.aspose.ms.System.TimeSpan
### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public System.TimeSpan getResourceLoadingTimeout()
```


Χρόνος λήξης για τη φόρτωση εξωτερικών πόρων


**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```


Χρόνος λήξης για τη φόρτωση εξωτερικών πόρων (setter)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### setTimeZoneOffset(Double value) {#setTimeZoneOffset-java.lang.Double-}
```
public final void setTimeZoneOffset(Double value)
```


Λαμβάνει ή ορίζει την απόκλιση του Συντονισμένου Παγκόσμιου Χρόνου (UTC) για τις ημερομηνίες των μηνυμάτων. Αυτή η ιδιότητα ορίζει τη διαφορά ζώνης ώρας μεταξύ της τοπικής ώρας και του UTC.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Κλωνοποιεί την τρέχουσα παρουσία.


**Returns:**
java.lang.Object -
### getFieldTextMap() {#getFieldTextMap--}
```
public Map<EmailField,String> getFieldTextMap()
```


Λαμβάνει τη χαρτογράφηση μεταξύ του μηνύματος email και της αναπαράστασης κειμένου πεδίου


**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - αντιστοίχηση

### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


Ορίζει τη χαρτογράφηση μεταξύ του μηνύματος email και της αναπαράστασης κειμένου πεδίου


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | αντιστοίχηση |
|

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


Ορίζει αν χρειάζεται να διατηρηθεί η αρχική συμβολοσειρά κεφαλίδας ημερομηνίας στο μήνυμα email κατά την αποθήκευση ή όχι (Προεπιλεγμένη τιμή είναι true)


**Returns:**
boolean - διατήρηση αρχικής ημερομηνίας εάν true

### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


Ορίζει αν χρειάζεται να διατηρηθεί η αρχική συμβολοσειρά κεφαλίδας ημερομηνίας στο μήνυμα email κατά την αποθήκευση ή όχι


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | preserveOriginalDate | boolean | διατήρηση αρχικής ημερομηνίας |
|

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

### isDisplayAttachments() {#isDisplayAttachments--}
```
public boolean isDisplayAttachments()
```


Λαμβάνει την επιλογή για εμφάνιση ή απόκρυψη συνημμένων στην κεφαλίδα. Προεπιλογή: true.


**Returns:**
boolean
### setDisplayAttachments(boolean displayAttachments) {#setDisplayAttachments-boolean-}
```
public void setDisplayAttachments(boolean displayAttachments)
```


Ορίζει την επιλογή για εμφάνιση ή απόκρυψη συνημμένων στην κεφαλίδα.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| displayAttachments | boolean |  |

### isDisplaySubject() {#isDisplaySubject--}
```
public boolean isDisplaySubject()
```


Λαμβάνει την επιλογή για εμφάνιση ή απόκρυψη του θέματος στην κεφαλίδα. Προεπιλογή: true.


**Returns:**
boolean
### setDisplaySubject(boolean displaySubject) {#setDisplaySubject-boolean-}
```
public void setDisplaySubject(boolean displaySubject)
```


Ορίζει την επιλογή για εμφάνιση ή απόκρυψη του θέματος στην κεφαλίδα


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| displaySubject | boolean |  |

### isDisplaySent() {#isDisplaySent--}
```
public boolean isDisplaySent()
```


Λαμβάνει την επιλογή για εμφάνιση ή απόκρυψη της ημερομηνίας/ώρας αποστολής στην κεφαλίδα. Προεπιλογή: true.


**Returns:**
boolean
### setDisplaySent(boolean displaySent) {#setDisplaySent-boolean-}
```
public void setDisplaySent(boolean displaySent)
```


Ορίζει την επιλογή για εμφάνιση ή απόκρυψη της ημερομηνίας/ώρας αποστολής στην κεφαλίδα.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| displaySent | boolean |  |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Παραλείπει τη φόρτωση πόρων http εάν true


**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| skipExternalResources | boolean |  |

