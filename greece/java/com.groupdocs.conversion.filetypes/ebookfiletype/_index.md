---
title: "EBookFileType"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ορίζει έγγραφα CAD (Computer Aided Design) που χρησιμοποιούνται για μορφές αρχείων 3D γραφικών και μπορεί να περιέχουν σχέδια 2D ή 3D."
type: docs
weight: 14
url: /el/java/com.groupdocs.conversion.filetypes/ebookfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EBookFileType extends FileType implements Serializable
```

Ορίζει έγγραφα CAD (Computer Aided Design) που χρησιμοποιούνται για μορφές αρχείων 3D γραφικών και μπορεί να περιέχουν σχεδιασμούς 2D ή 3D.
Περιλαμβάνει τους ακόλουθους τύπους:
[Epub](../../com.groupdocs.conversion.filetypes/ebookfiletype#Epub),
[Mobi](../../com.groupdocs.conversion.filetypes/ebookfiletype#Mobi),
[Azw3](../../com.groupdocs.conversion.filetypes/ebookfiletype#Azw3),
Μάθετε περισσότερα για τις μορφές CAD [εδώ](../https://wiki.fileformat.com/cad).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [EBookFileType()](#EBookFileType--) | Κατασκευαστής σειριοποίησης |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Epub](#Epub) | Η επέκταση EPUB είναι μια μορφή αρχείου e-book που παρέχει ένα τυποποιημένο ψηφιακό μορφότυπο δημοσίευσης για εκδότες και καταναλωτές. |
|
|  | [Mobi](#Mobi) | Η μορφή αρχείου MOBI είναι μία από τις πιο ευρέως χρησιμοποιούμενες μορφές αρχείων ebook. |
|
|  | [Azw3](#Azw3) | Το AZW3, επίσης γνωστό ως Kindle Format 8 (KF8), είναι η τροποποιημένη έκδοση της ψηφιακής μορφής αρχείου ebook AZW που αναπτύχθηκε για συσκευές Amazon Kindle. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### EBookFileType() {#EBookFileType--}
```
public EBookFileType()
```


Κατασκευαστής σειριοποίησης


### Epub {#Epub}
```
public static final EBookFileType Epub
```


Η επέκταση EPUB είναι μια μορφή αρχείου e-book που παρέχει ένα τυποποιημένο ψηφιακό μορφότυπο δημοσίευσης για εκδότες και καταναλωτές. Η μορφή αυτή είναι πλέον τόσο διαδεδομένη που υποστηρίζεται από πολλούς αναγνώστες e‑book και λογισμικά. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/ebook/epub).


### Mobi {#Mobi}
```
public static final EBookFileType Mobi
```


Η μορφή αρχείου MOBI είναι μία από τις πιο ευρέως χρησιμοποιούμενες μορφές αρχείων ebook. Η μορφή αυτή αποτελεί βελτίωση της παλιάς μορφής OEB (Open Ebook Format) και χρησιμοποιήθηκε ως ιδιόκτητη μορφή για το Mobipocket Reader. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/ebook/mobi).


### Azw3 {#Azw3}
```
public static final EBookFileType Azw3
```


Το AZW3, επίσης γνωστό ως Kindle Format 8 (KF8), είναι η τροποποιημένη έκδοση της ψηφιακής μορφής αρχείου ebook AZW που αναπτύχθηκε για συσκευές Amazon Kindle. Η μορφή αυτή αποτελεί βελτίωση των παλαιότερων αρχείων AZW και χρησιμοποιείται μόνο σε συσκευές Kindle Fire με συμβατότητα προς τα πίσω για τις προγενέστερες μορφές αρχείων, δηλαδή MOBI και AZW. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://docs.fileformat.com/ebook/azw3/).


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
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
