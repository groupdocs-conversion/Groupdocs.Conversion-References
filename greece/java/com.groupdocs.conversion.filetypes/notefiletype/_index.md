---
title: "NoteFileType"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ορίζει μορφές λήψης σημειώσεων."
type: docs
weight: 19
url: /el/java/com.groupdocs.conversion.filetypes/notefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class NoteFileType extends FileType
```

Ορίζει μορφές σημειώσεων. Περιλαμβάνει τους παρακάτω τύπους αρχείων:
[One](../../com.groupdocs.conversion.filetypes/notefiletype#One).
Μάθετε περισσότερα για τις μορφές σημειώσεων [εδώ](../https://wiki.fileformat.com/note-taking).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [NoteFileType()](#NoteFileType--) | Κατασκευαστής σειριοποίησης |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [One](#One) | Αρχεία με επέκταση .ONE δημιουργούνται από την εφαρμογή Microsoft OneNote. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### NoteFileType() {#NoteFileType--}
```
public NoteFileType()
```


Κατασκευαστής σειριοποίησης


### One {#One}
```
public static final NoteFileType One
```


Αρχεία με επέκταση .ONE δημιουργούνται από την εφαρμογή Microsoft OneNote. Το OneNote σας επιτρέπει να συλλέγετε πληροφορίες χρησιμοποιώντας την εφαρμογή σαν να χρησιμοποιείτε το σημειωματάριό σας για τη λήψη σημειώσεων.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/note-taking/one).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Προετοιμάστηκαν προεπιλεγμένες επιλογές φόρτωσης για τον τύπο πηγαίου αρχείου


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
