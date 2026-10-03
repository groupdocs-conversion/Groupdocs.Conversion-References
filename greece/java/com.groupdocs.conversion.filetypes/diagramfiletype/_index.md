---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ορίζει έγγραφα διαγράμματος."
type: docs
weight: 13
url: /el/java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

Ορίζει έγγραφα Diagram. Περιλαμβάνει τους ακόλουθους τύπους:
[Vdw](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdw),
[Vdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdx),
[Vsd](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsd),
[Vsdm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdm),
[Vsdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdx),
[Vss](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vss),
[Vssm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssm),
[Vssx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssx),
[Vst](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vst),
[Vstm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstm),
[Vstx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstx),
[Vsx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsx),
[Vtx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vtx).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [DiagramFileType()](#DiagramFileType--) | Κατασκευαστής σειριοποίησης |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Vsd](#Vsd) | Τα αρχεία VSD είναι σχέδια που δημιουργούνται με την εφαρμογή Microsoft Visio για να αντιπροσωπεύουν ποικιλία γραφικών αντικειμένων και τη διασύνδεσή τους. |
|
|  | [Vsdx](#Vsdx) | Τα αρχεία με επέκταση .VSDX αντιπροσωπεύουν τη μορφή αρχείου Microsoft Visio που εισήχθη από το Microsoft Office 2013 και μετά. |
|
|  | [Vss](#Vss) | Τα VSS είναι αρχεία προτύπων που δημιουργήθηκαν με το Microsoft Visio 2007 και παλαιότερα. |
|
|  | [Vst](#Vst) | Τα αρχεία με επέκταση VST είναι αρχεία διανυσματικών εικόνων που δημιουργούνται με το Microsoft Visio και λειτουργούν ως πρότυπο για τη δημιουργία περαιτέρω αρχείων. |
|
|  | [Vsx](#Vsx) | Τα αρχεία με επέκταση .VSX αναφέρονται σε πρότυπα (stencils) που αποτελούνται από σχέδια και σχήματα που χρησιμοποιούνται για τη δημιουργία διαγραμμάτων στο Microsoft Visio. |
|
|  | [Vtx](#Vtx) | Ένα αρχείο με επέκταση VTX είναι πρότυπο σχεδίου Microsoft Visio που αποθηκεύεται στο δίσκο σε μορφή XML. |
|
|  | [Vdw](#Vdw) | Το VDW είναι η μορφή αρχείου Visio Graphics Service που καθορίζει τις ροές και τις αποθηκεύσεις που απαιτούνται για την απόδοση ενός web σχεδίου. |
|
|  | [Vdx](#Vdx) | Οποιοδήποτε σχέδιο ή διάγραμμα δημιουργηθεί στο Microsoft Visio, αλλά αποθηκευτεί σε μορφή XML, έχει επέκταση .VDX. |
|
|  | [Vssx](#Vssx) | Τα αρχεία με επέκταση .VSSX είναι πρότυπα σχεδίων που δημιουργήθηκαν με το Microsoft Visio 2013 και μεταγενέστερα. |
|
|  | [Vstx](#Vstx) | Τα αρχεία με επέκταση VSTX είναι αρχεία προτύπων σχεδίων που δημιουργήθηκαν με το Microsoft Visio 2013 και μεταγενέστερα. |
|
|  | [Vsdm](#Vsdm) | Τα αρχεία με επέκταση VSDM είναι αρχεία σχεδίων που δημιουργήθηκαν με την εφαρμογή Microsoft Visio που υποστηρίζει μακροεντολές. |
|
|  | [Vssm](#Vssm) | Τα αρχεία με επέκταση .VSSM είναι αρχεία προτύπων Microsoft Visio που παρέχουν υποστήριξη για μακροεντολές. |
|
|  | [Vstm](#Vstm) | Τα αρχεία με επέκταση VSTM είναι αρχεία προτύπων που δημιουργήθηκαν με το Microsoft Visio και υποστηρίζουν μακροεντολές. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### DiagramFileType() {#DiagramFileType--}
```
public DiagramFileType()
```


Κατασκευαστής σειριοποίησης


### Vsd {#Vsd}
```
public static final DiagramFileType Vsd
```


Τα αρχεία VSD είναι σχέδια που δημιουργούνται με την εφαρμογή Microsoft Visio για να αντιπροσωπεύουν ποικιλία γραφικών αντικειμένων και τη διασύνδεσή τους.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/image/vsd).


### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


Τα αρχεία με επέκταση .VSDX αντιπροσωπεύουν τη μορφή αρχείου Microsoft Visio που εισήχθη από το Microsoft Office 2013 και μετά. Αναπτύχθηκε για να αντικαταστήσει τη δυαδική μορφή αρχείου, .VSD, η οποία υποστηρίζεται από παλαιότερες εκδόσεις του Microsoft Visio.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/image/vsdx).


### Vss {#Vss}
```
public static final DiagramFileType Vss
```


Τα VSS είναι αρχεία προτύπων που δημιουργήθηκαν με το Microsoft Visio 2007 και παλαιότερα. Τα αρχεία προτύπων παρέχουν αντικείμενα σχεδίου που μπορούν να συμπεριληφθούν σε ένα σχέδιο .VSD του Visio.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/image/vss).


### Vst {#Vst}
```
public static final DiagramFileType Vst
```


Τα αρχεία με επέκταση VST είναι αρχεία διανυσματικών εικόνων που δημιουργούνται με το Microsoft Visio και λειτουργούν ως πρότυπο για τη δημιουργία περαιτέρω αρχείων. Αυτά τα αρχεία προτύπων είναι σε δυαδική μορφή αρχείου και περιέχουν την προεπιλεγμένη διάταξη και ρυθμίσεις που χρησιμοποιούνται για τη δημιουργία νέων σχεδίων Visio.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/image/vst).


### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


Τα αρχεία με επέκταση .VSX αναφέρονται σε πρότυπα που αποτελούνται από σχέδια και σχήματα που χρησιμοποιούνται για τη δημιουργία διαγραμμάτων στο Microsoft Visio. Τα αρχεία VSX αποθηκεύονται σε μορφή XML και υποστηρίζονταν μέχρι το Visio 2013.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/image/vsx).


### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


Ένα αρχείο με επέκταση VTX είναι πρότυπο σχεδίου Microsoft Visio που αποθηκεύεται στο δίσκο σε μορφή XML. Το πρότυπο στοχεύει να παρέχει ένα αρχείο με βασικές ρυθμίσεις που μπορούν να χρησιμοποιηθούν για τη δημιουργία πολλαπλών αρχείων Visio με τις ίδιες ρυθμίσεις.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/image/vtx).


### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


Το VDW είναι η μορφή αρχείου Visio Graphics Service που καθορίζει τις ροές και τις αποθηκεύσεις που απαιτούνται για την απόδοση ενός web σχεδίου.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/web/vdw).


### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


Οποιοδήποτε σχέδιο ή διάγραμμα δημιουργείται στο Microsoft Visio, αλλά αποθηκεύεται σε μορφή XML, έχει επέκταση .VDX. Ένα αρχείο XML σχεδίου Visio δημιουργείται στο λογισμικό Visio, το οποίο αναπτύσσεται από τη Microsoft.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/image/vdx).


### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


Τα αρχεία με επέκταση .VSSX είναι πρότυπα σχεδίων που δημιουργούνται με το Microsoft Visio 2013 και νεότερες εκδόσεις. Η μορφή αρχείου VSSX μπορεί να ανοιχτεί με το Visio 2013 και νεότερες εκδόσεις. Τα αρχεία Visio είναι γνωστά για την αναπαράσταση μιας ποικιλίας στοιχείων σχεδίασης όπως συλλογή σχημάτων, συνδέσμων, διαγραμμάτων ροής, διατάξεων δικτύου, διαγραμμάτων UML,
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/image/vssx).


### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


Τα αρχεία με επέκταση VSTX είναι αρχεία προτύπων σχεδίων που δημιουργούνται με το Microsoft Visio 2013 και νεότερες εκδόσεις. Αυτά τα αρχεία VSTX παρέχουν σημείο εκκίνησης για τη δημιουργία σχεδίων Visio, αποθηκευμένα ως αρχεία .VSDX, με προεπιλεγμένη διάταξη και ρυθμίσεις.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/image/vstx).


### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


Τα αρχεία με επέκταση VSDM είναι αρχεία σχεδίων που δημιουργούνται με την εφαρμογή Microsoft Visio που υποστηρίζει μακροεντολές. Τα αρχεία VSDM είναι σχέδια OPC/XML που είναι παρόμοια με τα VSDX, αλλά παρέχουν επίσης τη δυνατότητα εκτέλεσης μακροεντολών όταν ανοίγεται το αρχείο.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/image/vsdm).


### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


Τα αρχεία με επέκταση .VSSM είναι αρχεία Stencil του Microsoft Visio που παρέχουν υποστήριξη για μακροεντολές. Ένα αρχείο VSSM όταν ανοίγεται επιτρέπει την εκτέλεση των μακροεντολών για την επίτευξη της επιθυμητής μορφοποίησης και τοποθέτησης των σχημάτων σε ένα διάγραμμα.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/image/vssm).


### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


Τα αρχεία με επέκταση VSTM είναι αρχεία προτύπων που δημιουργούνται με το Microsoft Visio και υποστηρίζουν μακροεντολές. Σε αντίθεση με τα αρχεία VSDX, τα αρχεία που δημιουργούνται από πρότυπα VSTM μπορούν να εκτελούν μακροεντολές που έχουν αναπτυχθεί σε κώδικα Visual Basic for Applications (VBA).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/image/vstm).


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
