---
title: "PossibleConversions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Αντιπροσωπεύει μια αντιστοίχιση των ζευγών μετατροπής που υποστηρίζονται για συγκεκριμένη μορφή αρχείου προέλευσης."
type: docs
weight: 13
url: /el/java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

Αντιπροσωπεύει μια αντιστοίχιση των ζευγών μετατροπής που υποστηρίζονται για συγκεκριμένη μορφή αρχείου προέλευσης.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | Δημιουργεί πιθανή λίστα μετατροπών για το καθορισμένο μορφότυπο πηγαίου αρχείου |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [NULL](#NULL) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getLoadOptions()](#getLoadOptions--) | Προκαθορισμένες επιλογές φόρτωσης που μπορούν να χρησιμοποιηθούν για μετατροπή από τον τρέχοντα τύπο |
|
|  | [getAll()](#getAll--) | Όλοι οι τύποι αρχείων-στόχων και η σημαία πρωτεύοντος/δευτερεύοντος |
|
|  | [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | Επιστρέφει τη μετατροπή-στόχο για τον καθορισμένο τύπο αρχείου-στόχου |
|
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
|  | [getPrimary()](#getPrimary--) | Πρωτεύοντες τύποι αρχείων-στόχων |
|
|  | [getSecondary()](#getSecondary--) | Δευτερεύοντες τύποι αρχείων-στόχων |
|
|  | [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | Προσθήκη ζεύγους μετατροπής |
|
|  | [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | Εύρεση ζεύγους μετατροπής στην τρέχουσα λίστα για τον τύπο αρχείου-στόχο |
|
|  | [getSource()](#getSource--) | Μορφότυποι πηγαίων αρχείων |
|
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


Δημιουργεί πιθανή λίστα μετατροπών για το καθορισμένο μορφότυπο πηγαίου αρχείου


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | τύπος πηγαίου αρχείου |
|

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Προκαθορισμένες επιλογές φόρτωσης που μπορούν να χρησιμοποιηθούν για μετατροπή από τον τρέχοντα τύπο


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options

### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


Όλοι οι τύποι αρχείων-στόχων και η σημαία πρωτεύοντος/δευτερεύοντος


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - Διαθέσιμος τύπος του [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)

### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


Επιστρέφει τη μετατροπή-στόχο για τον καθορισμένο τύπο αρχείου-στόχου


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | τύπος αρχείου προορισμού |
|

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) - conversions

### getTargetConversion(String extension) {#getTargetConversion-java.lang.String-}
```
public TargetConversion getTargetConversion(String extension)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| επέκταση | java.lang.String |  |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getPrimary() {#getPrimary--}
```
public Iterable<FileType> getPrimary()
```


Πρωτεύοντες τύποι αρχείων-στόχων


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - κύριοι τύποι αρχείων προορισμού

### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


Δευτερεύοντες τύποι αρχείων-στόχων


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - δευτερεύοντες τύποι αρχείων προορισμού

### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


Προσθήκη ζεύγους μετατροπής


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | ζεύγος μετατροπής |
|

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


Εύρεση ζεύγους μετατροπής στην τρέχουσα λίστα για τον τύπο αρχείου-στόχο


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | τύπος αρχείου προορισμού |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair

### getSource() {#getSource--}
```
public FileType getSource()
```


Μορφότυποι πηγαίων αρχείων


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats

