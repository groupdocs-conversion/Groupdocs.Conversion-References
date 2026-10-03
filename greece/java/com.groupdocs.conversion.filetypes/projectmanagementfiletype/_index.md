---
title: "ProjectManagementFileType"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ορίζει μορφότυπους αρχείων Project που δημιουργούνται από λογισμικό Διαχείρισης Έργου όπως το Microsoft Project, Primavera P6 κ.λπ."
type: docs
weight: 23
url: /el/java/com.groupdocs.conversion.filetypes/projectmanagementfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class ProjectManagementFileType extends FileType
```

Ορίζει μορφότυπους αρχείων Project που δημιουργούνται από λογισμικό Διαχείρισης Έργου όπως το Microsoft Project, Primavera P6 κ.λπ. Ένα αρχείο έργου είναι μια συλλογή εργασιών, πόρων και του χρονοπρογράμματός τους για την επίτευξη μετρήσιμου αποτελέσματος με τη μορφή προϊόντος ή υπηρεσίας.
Έγγραφα διαχείρισης έργου. Περιλαμβάνει τους παρακάτω τύπους αρχείων:
[Mpp](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpp),
[Mpt](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpt),
[Mpx](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpx).
Μάθετε περισσότερα για μορφότυπους Διαχείρισης Έργου [εδώ](../https://wiki.fileformat.com/project-management).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ProjectManagementFileType()](#ProjectManagementFileType--) | Κατασκευαστής σειριοποίησης |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Mpt](#Mpt) | Τα πρότυπα αρχείων Microsoft Project, περιέχουν βασικές πληροφορίες και δομή μαζί με ρυθμίσεις εγγράφου για τη δημιουργία αρχείων .MPP. |
|
|  | [Mpp](#Mpp) | Το MPP είναι αρχείο δεδομένων Microsoft Project που αποθηκεύει πληροφορίες σχετικές με τη διαχείριση έργου με ολοκληρωμένο τρόπο. |
|
|  | [Mpx](#Mpx) | Το Microsoft Exchange File Format είναι ένα αρχείο ASCII για τη μεταφορά πληροφοριών έργου μεταξύ Microsoft Project (MSP) και άλλων εφαρμογών που υποστηρίζουν το αρχείο MPX όπως το Primavera Project Planner, Sciforma και Timerline Precision Estimating. |
|
|  | [Xer](#Xer) | Ο μορφότυπος αρχείου XER είναι ένας ιδιόκτητος μορφότυπος αρχείου έργου που χρησιμοποιείται από την εφαρμογή προγραμματισμού και διαχείρισης έργου Primavera P6. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ProjectManagementFileType() {#ProjectManagementFileType--}
```
public ProjectManagementFileType()
```


Κατασκευαστής σειριοποίησης


### Mpt {#Mpt}
```
public static final ProjectManagementFileType Mpt
```


Τα πρότυπα αρχείων Microsoft Project, περιέχουν βασικές πληροφορίες και δομή μαζί με ρυθμίσεις εγγράφου για τη δημιουργία αρχείων .MPP.
Μάθετε περισσότερα για αυτόν τον μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/project-management/mpt).


### Mpp {#Mpp}
```
public static final ProjectManagementFileType Mpp
```


Το MPP είναι αρχείο δεδομένων Microsoft Project που αποθηκεύει πληροφορίες σχετικές με τη διαχείριση έργου με ολοκληρωμένο τρόπο.
Μάθετε περισσότερα για αυτόν τον μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/project-management/mpp).


### Mpx {#Mpx}
```
public static final ProjectManagementFileType Mpx
```


Το Microsoft Exchange File Format είναι ένα αρχείο ASCII για τη μεταφορά πληροφοριών έργου μεταξύ Microsoft Project (MSP) και άλλων εφαρμογών που υποστηρίζουν το αρχείο MPX όπως το Primavera Project Planner, Sciforma και Timerline Precision Estimating.
Μάθετε περισσότερα για αυτόν τον μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/project-management/mpx).


### Xer {#Xer}
```
public static final ProjectManagementFileType Xer
```


Ο μορφότυπος αρχείου XER είναι ένας ιδιόκτητος μορφότυπος αρχείου έργου που χρησιμοποιείται από την εφαρμογή προγραμματισμού και διαχείρισης έργου Primavera P6.
Μάθετε περισσότερα για αυτόν τον μορφότυπο αρχείου [εδώ](../https://docs.fileformat.com/project-management/xer).


### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Προετοιμάστηκαν προεπιλεγμένες επιλογές μετατροπής για τον τύπο αρχείου


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
