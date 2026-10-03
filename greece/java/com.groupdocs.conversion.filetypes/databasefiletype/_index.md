---
title: "DatabaseFileType"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ορίζει έγγραφα CAD (Computer Aided Design) που χρησιμοποιούνται για μορφές αρχείων 3D γραφικών και μπορεί να περιέχουν σχέδια 2D ή 3D."
type: docs
weight: 12
url: /el/java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

Ορίζει έγγραφα CAD (Computer Aided Design) που χρησιμοποιούνται για μορφές αρχείων 3D γραφικών και μπορεί να περιέχουν σχεδιασμούς 2D ή 3D.
Περιλαμβάνει τους ακόλουθους τύπους:
[Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype#Nsf),
[Log](../../com.groupdocs.conversion.filetypes/databasefiletype#Log),
[Sql](../../com.groupdocs.conversion.filetypes/databasefiletype#Sql),
Μάθετε περισσότερα για τις μορφές CAD [εδώ](../https://wiki.fileformat.com/cad).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [DatabaseFileType()](#DatabaseFileType--) | Κατασκευαστής σειριοποίησης |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Nsf](#Nsf) | Ένα αρχείο με επέκταση .nsf (Notes Storage Facility) είναι μια μορφή αρχείου βάσης δεδομένων που χρησιμοποιείται από το λογισμικό IBM Notes, που προηγουμένως ήταν γνωστό ως Lotus Notes. |
|
|  | [Log](#Log) | Ένα αρχείο με επέκταση .log περιέχει μια λίστα απλού κειμένου με χρονική σήμανση. |
|
|  | [Sql](#Sql) | Ένα αρχείο με επέκταση .sql είναι ένα αρχείο Structured Query Language (SQL) που περιέχει κώδικα για εργασία με σχεσιακές βάσεις δεδομένων. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### DatabaseFileType() {#DatabaseFileType--}
```
public DatabaseFileType()
```


Κατασκευαστής σειριοποίησης


### Nsf {#Nsf}
```
public static final DatabaseFileType Nsf
```


Ένα αρχείο με επέκταση .nsf (Notes Storage Facility) είναι μια μορφή αρχείου βάσης δεδομένων που χρησιμοποιείται από το λογισμικό IBM Notes, που προηγουμένως ήταν γνωστό ως Lotus Notes. Ορίζει το σχήμα για την αποθήκευση διαφορετικών τύπων αντικειμένων όπως email, ραντεβού, έγγραφα, φόρμες και προβολές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://docs.fileformat.com/database/nsf).


### Log {#Log}
```
public static final DatabaseFileType Log
```


Ένα αρχείο με επέκταση .log περιέχει μια λίστα απλού κειμένου με χρονική σήμανση. Συνήθως, λεπτομέρειες συγκεκριμένων δραστηριοτήτων καταγράφονται από λογισμικά ή λειτουργικά συστήματα για να βοηθήσουν τους προγραμματιστές ή τους χρήστες να παρακολουθήσουν τι συνέβαινε σε μια συγκεκριμένη χρονική περίοδο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://docs.fileformat.com/database/log).


### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


Ένα αρχείο με επέκταση .sql είναι ένα αρχείο Structured Query Language (SQL) που περιέχει κώδικα για εργασία με σχεσιακές βάσεις δεδομένων. Χρησιμοποιείται για τη σύνταξη δηλώσεων SQL για λειτουργίες CRUD (Create, Read, Update, and Delete) σε βάσεις δεδομένων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://docs.fileformat.com/database/sql).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Προετοιμάστηκαν προεπιλεγμένες επιλογές φόρτωσης για τον τύπο πηγαίου αρχείου


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
