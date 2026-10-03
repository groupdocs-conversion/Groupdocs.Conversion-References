---
title: "PdfFileType"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ορίζει έγγραφα PDF."
type: docs
weight: 21
url: /el/java/com.groupdocs.conversion.filetypes/pdffiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFileType extends FileType implements Serializable
```

Ορίζει έγγραφα Pdf. Περιλαμβάνει τους ακόλουθους τύπους αρχείων:
[Pdf](../../com.groupdocs.conversion.filetypes/pdffiletype#Pdf),

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PdfFileType()](#PdfFileType--) | Κατασκευαστής σειριοποίησης |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Pdf](#Pdf) | Το Portable Document Format (PDF) είναι ένας τύπος εγγράφου που δημιουργήθηκε από την Adobe τη δεκαετία του 1990. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PdfFileType() {#PdfFileType--}
```
public PdfFileType()
```


Κατασκευαστής σειριοποίησης


### Pdf {#Pdf}
```
public static final PdfFileType Pdf
```


Το Portable Document Format (PDF) είναι ένας τύπος εγγράφου που δημιουργήθηκε από την Adobe τη δεκαετία του 1990. Ο σκοπός αυτού του μορφότυπου αρχείου ήταν η εισαγωγή ενός προτύπου για την αναπαράσταση εγγράφων και άλλου αναφορικού υλικού σε μορφή που είναι ανεξάρτητη από λογισμικό εφαρμογών, υλικό καθώς και λειτουργικό σύστημα.
Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/view/pdf).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Προετοιμάστηκαν προεπιλεγμένες επιλογές φόρτωσης για τον τύπο πηγαίου αρχείου


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Προετοιμάστηκαν προεπιλεγμένες επιλογές μετατροπής για τον τύπο αρχείου


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
