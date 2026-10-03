---
title: "MboxLoadOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές φόρτωσης εγγράφων Mbox."
type: docs
weight: 23
url: /el/java/com.groupdocs.conversion.options.load/mboxloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class MboxLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Επιλογές φόρτωσης εγγράφων Mbox.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [MboxLoadOptions()](#MboxLoadOptions--) | Αρχικοποιεί νέα παρουσία της κλάσης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isConvertOwner()](#isConvertOwner--) | Ο ιδιοκτήτης δεν θα μετατραπεί |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} Προεπιλογή: 3 |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | {@inheritDoc} |
|
### MboxLoadOptions() {#MboxLoadOptions--}
```
public MboxLoadOptions()
```


Αρχικοποιεί νέα παρουσία της κλάσης.


### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Ο ιδιοκτήτης δεν θα μετατραπεί


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


Επιλογή για τον έλεγχο του πόσων επιπέδων σε βάθος θα εκτελεστεί η μετατροπή Προεπιλογή: 3


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

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
