---
title: "PersonalStorageLoadOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές φόρτωσης εγγράφων προσωπικής αποθήκευσης."
type: docs
weight: 28
url: /el/java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Επιλογές φόρτωσης εγγράφων προσωπικής αποθήκευσης.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | Αρχικοποιεί νέα παρουσία της κλάσης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFolder()](#getFolder--) | Φάκελος που θα υποβληθεί σε επεξεργασία. Η προεπιλεγμένη τιμή είναι Inbox |
|
|  | [setFolder(String folder)](#setFolder-java.lang.String-) | Ορίστε το φάκελο που θα υποβληθεί σε επεξεργασία |
|
|  | [isConvertOwner()](#isConvertOwner--) | {@inheritDoc} Ο κάτοχος δεν θα μετατραπεί |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


Αρχικοποιεί νέα παρουσία της κλάσης.


### getFolder() {#getFolder--}
```
public String getFolder()
```


Φάκελος που θα υποβληθεί σε επεξεργασία. Η προεπιλεγμένη τιμή είναι Inbox


**Returns:**
java.lang.String - Φάκελος που θα υποβληθεί σε επεξεργασία

### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


Ορίστε το φάκελο που θα υποβληθεί σε επεξεργασία


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | φάκελος | java.lang.String | φάκελος |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Λαμβάνει επιλογή για να ελέγξει εάν το ίδιο το δοχείο εγγράφων πρέπει να μετατραπεί. Ο κάτοχος δεν θα μετατραπεί


**Returns:**
boolean
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Επιλογή για έλεγχο του αν τα ιδιόκτητα έγγραφα στο δοχείο εγγράφων πρέπει να μετατραπούν


**Returns:**
boolean
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

