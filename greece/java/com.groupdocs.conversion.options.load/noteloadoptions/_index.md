---
title: "NoteLoadOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές φόρτωσης εγγράφων One."
type: docs
weight: 24
url: /el/java/com.groupdocs.conversion.options.load/noteloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class NoteLoadOptions extends LoadOptions implements Serializable
```

Επιλογές φόρτωσης εγγράφων One.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [NoteLoadOptions()](#NoteLoadOptions--) | Αρχικοποιεί νέα παρουσία της κλάσης [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Προεπιλεγμένη γραμματοσειρά για το έγγραφο Note. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Προεπιλεγμένη γραμματοσειρά για το έγγραφο Note. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Αντικαθιστά συγκεκριμένες γραμματοσειρές κατά τη μετατροπή του εγγράφου Note. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Αντικαθιστά συγκεκριμένες γραμματοσειρές κατά τη μετατροπή του εγγράφου Note. |
|
|  | [getPassword()](#getPassword--) | Ορίστε κωδικό πρόσβασης για την αποπροστασία του προστατευμένου εγγράφου. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ορίστε κωδικό πρόσβασης για την αποπροστασία του προστατευμένου εγγράφου. |
|
### NoteLoadOptions() {#NoteLoadOptions--}
```
public NoteLoadOptions()
```


Αρχικοποιεί νέα παρουσία της κλάσης [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions).


### getFormat() {#getFormat--}
```
public final NoteFileType getFormat()
```


Τύπος αρχείου εισαγόμενου εγγράφου


**Returns:**
[NoteFileType](../../com.groupdocs.conversion.filetypes/notefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Προεπιλεγμένη γραμματοσειρά για το έγγραφο Note. Η παρακάτω γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Προεπιλεγμένη γραμματοσειρά για το έγγραφο Note. Η παρακάτω γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Αντικαθιστά συγκεκριμένες γραμματοσειρές κατά τη μετατροπή του εγγράφου Note.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Αντικαθιστά συγκεκριμένες γραμματοσειρές κατά τη μετατροπή του εγγράφου Note.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

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

