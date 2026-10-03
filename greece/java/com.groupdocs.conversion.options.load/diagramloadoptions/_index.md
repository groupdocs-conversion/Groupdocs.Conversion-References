---
title: "DiagramLoadOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές φόρτωσης εγγράφων διαγράμματος."
type: docs
weight: 15
url: /el/java/com.groupdocs.conversion.options.load/diagramloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramLoadOptions extends LoadOptions implements Serializable
```

Επιλογές φόρτωσης εγγράφων διαγράμματος.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [DiagramLoadOptions()](#DiagramLoadOptions--) | Αρχικοποιεί νέα παρουσία της κλάσης [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Προεπιλεγμένη γραμματοσειρά για το έγγραφο Diagram. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Προεπιλεγμένη γραμματοσειρά για το έγγραφο Diagram. |
|
### DiagramLoadOptions() {#DiagramLoadOptions--}
```
public DiagramLoadOptions()
```


Αρχικοποιεί νέα παρουσία της κλάσης [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions).


### getFormat() {#getFormat--}
```
public final DiagramFileType getFormat()
```


Τύπος αρχείου εισαγόμενου εγγράφου


**Returns:**
[DiagramFileType](../../com.groupdocs.conversion.filetypes/diagramfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Προεπιλεγμένη γραμματοσειρά για το έγγραφο Diagram. Η παρακάτω γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Προεπιλεγμένη γραμματοσειρά για το έγγραφο Diagram. Η παρακάτω γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

