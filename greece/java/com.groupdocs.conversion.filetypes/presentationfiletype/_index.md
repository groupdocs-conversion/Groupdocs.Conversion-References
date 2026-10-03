---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ορίζει μορφές αρχείων παρουσίασης που αποθηκεύουν μια συλλογή εγγραφών για να φιλοξενήσουν δεδομένα παρουσίασης όπως διαφάνειες, σχήματα, κείμενο, κινούμενα σχέδια, βίντεο, ήχο και ενσωματωμένα αντικείμενα."
type: docs
weight: 22
url: /el/java/com.groupdocs.conversion.filetypes/presentationfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PresentationFileType extends FileType implements Serializable
```

Ορίζει μορφές αρχείων παρουσίασης που αποθηκεύουν συλλογή εγγραφών για τη διαχείριση δεδομένων παρουσίασης όπως διαφάνειες, σχήματα, κείμενο, κινούμενα σχέδια, βίντεο, ήχο και ενσωματωμένα αντικείμενα.
Περιλαμβάνει τους ακόλουθους τύπους αρχείων:
[Odp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Odp),
[Otp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Otp),
[Pot](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pot),
[Potm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potm),
[Potx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potx),
[Pps](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pps),
[Ppsm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsm),
[Ppsx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsx),
[Ppt](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppt),
[Pptm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptm),
[Pptx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptx).
Μάθετε περισσότερα για τις μορφές Παρουσίασης [εδώ](../https://wiki.fileformat.com/presentation).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PresentationFileType()](#PresentationFileType--) | Κατασκευαστής σειριοποίησης |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Ppt](#Ppt) | Ένα αρχείο με επέκταση PPT αντιπροσωπεύει αρχείο PowerPoint που αποτελείται από μια συλλογή διαφανειών για προβολή ως SlideShow. |
|
|  | [Pps](#Pps) | Τα αρχεία PPS, PowerPoint Slide Show, δημιουργούνται χρησιμοποιώντας το Microsoft PowerPoint για σκοπό Slide Show. |
|
|  | [Pptx](#Pptx) | Τα αρχεία με επέκταση PPTX είναι αρχεία παρουσίασης που δημιουργήθηκαν με τη δημοφιλής εφαρμογή Microsoft PowerPoint. |
|
|  | [Ppsx](#Ppsx) | Τα αρχεία PPSX, Power Point Slide Show, δημιουργούνται χρησιμοποιώντας το Microsoft PowerPoint 2007 και νεότερες εκδόσεις για σκοπό Slide Show. |
|
|  | [Odp](#Odp) | Τα αρχεία με επέκταση ODP αντιπροσωπεύουν μορφή αρχείου παρουσίασης που χρησιμοποιείται από το OpenOffice.org στο πρότυπο OASISOpen. |
|
|  | [Otp](#Otp) | Τα αρχεία με επέκταση .OTP αντιπροσωπεύουν πρότυπα αρχείων παρουσίασης που δημιουργούνται από εφαρμογές στο πρότυπο μορφής OASIS OpenDocument. |
|
|  | [Potx](#Potx) | Τα αρχεία με επέκταση .POTX αντιπροσωπεύουν πρότυπα παρουσιάσεων Microsoft PowerPoint που δημιουργούνται με το Microsoft PowerPoint 2007 και νεότερες εκδόσεις. |
|
|  | [Pot](#Pot) | Τα αρχεία με επέκταση .POT αντιπροσωπεύουν πρότυπα αρχείων Microsoft PowerPoint που δημιουργήθηκαν από τις εκδόσεις PowerPoint 97-2003. |
|
|  | [Potm](#Potm) | Τα αρχεία με επέκταση POTM είναι πρότυπα αρχείων Microsoft PowerPoint με υποστήριξη για Macros. |
|
|  | [Pptm](#Pptm) | Τα αρχεία με επέκταση PPTM είναι αρχεία παρουσίασης με ενεργοποιημένα Macros που δημιουργούνται με το Microsoft PowerPoint 2007 ή νεότερες εκδόσεις. |
|
|  | [Ppsm](#Ppsm) | Τα αρχεία με επέκταση PPSM αντιπροσωπεύουν μορφή αρχείου Slide Show με ενεργοποιημένα Macros που δημιουργήθηκε με το Microsoft PowerPoint 2007 ή νεότερες εκδόσεις. |
|
|  | [Fodp](#Fodp) | Τα αρχεία με επέκταση FODP αντιπροσωπεύουν παρουσίαση OpenDocument Flat XML. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PresentationFileType() {#PresentationFileType--}
```
public PresentationFileType()
```


Κατασκευαστής σειριοποίησης


### Ppt {#Ppt}
```
public static final PresentationFileType Ppt
```


Ένα αρχείο με επέκταση PPT αντιπροσωπεύει αρχείο PowerPoint που αποτελείται από μια συλλογή διαφανειών για προβολή ως SlideShow. Καθορίζει τη Δυαδική Μορφή Αρχείου που χρησιμοποιείται από το Microsoft PowerPoint 97-2003.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/presentation/ppt).


### Pps {#Pps}
```
public static final PresentationFileType Pps
```


Τα αρχεία PPS, PowerPoint Slide Show, δημιουργούνται χρησιμοποιώντας το Microsoft PowerPoint για σκοπό Slide Show. Η ανάγνωση και δημιουργία αρχείων PPS υποστηρίζεται από το Microsoft PowerPoint 97-2003.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/presentation/pps).


### Pptx {#Pptx}
```
public static final PresentationFileType Pptx
```


Τα αρχεία με επέκταση PPTX είναι αρχεία παρουσίασης που δημιουργήθηκαν με τη δημοφιλής εφαρμογή Microsoft PowerPoint. Σε αντίθεση με την προηγούμενη έκδοση μορφής αρχείου παρουσίασης PPT που ήταν δυαδική, η μορφή PPTX βασίζεται στη μορφή αρχείου παρουσίασης open XML του Microsoft PowerPoint.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/presentation/pptx).


### Ppsx {#Ppsx}
```
public static final PresentationFileType Ppsx
```


Τα αρχεία PPSX, Power Point Slide Show, δημιουργούνται χρησιμοποιώντας το Microsoft PowerPoint 2007 και νεότερες εκδόσεις για σκοπό Slide Show.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/presentation/ppsx).


### Odp {#Odp}
```
public static final PresentationFileType Odp
```


Τα αρχεία με επέκταση ODP αντιπροσωπεύουν μορφή αρχείου παρουσίασης που χρησιμοποιείται από το OpenOffice.org στο πρότυπο OASISOpen.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/presentation/odp).


### Otp {#Otp}
```
public static final PresentationFileType Otp
```


Τα αρχεία με επέκταση .OTP αντιπροσωπεύουν πρότυπα αρχείων παρουσίασης που δημιουργούνται από εφαρμογές στο πρότυπο μορφής OASIS OpenDocument.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/presentation/otp).


### Potx {#Potx}
```
public static final PresentationFileType Potx
```


Τα αρχεία με επέκταση .POTX αντιπροσωπεύουν πρότυπα παρουσιάσεων Microsoft PowerPoint που δημιουργούνται με το Microsoft PowerPoint 2007 και νεότερες εκδόσεις.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/presentation/potx).


### Pot {#Pot}
```
public static final PresentationFileType Pot
```


Τα αρχεία με επέκταση .POT αντιπροσωπεύουν πρότυπα αρχείων Microsoft PowerPoint που δημιουργήθηκαν από τις εκδόσεις PowerPoint 97-2003.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/presentation/pot).


### Potm {#Potm}
```
public static final PresentationFileType Potm
```


Τα αρχεία με την επέκταση POTM είναι αρχεία προτύπων Microsoft PowerPoint με υποστήριξη για Μακροεντολές. Τα αρχεία POTM δημιουργούνται με το PowerPoint 2007 ή νεότερο και περιέχουν προεπιλεγμένες ρυθμίσεις που μπορούν να χρησιμοποιηθούν για τη δημιουργία περαιτέρω αρχείων παρουσίασης.
Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/presentation/potm).


### Pptm {#Pptm}
```
public static final PresentationFileType Pptm
```


Τα αρχεία με επέκταση PPTM είναι αρχεία παρουσίασης με ενεργοποιημένα Macros που δημιουργούνται με το Microsoft PowerPoint 2007 ή νεότερες εκδόσεις.
Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/presentation/pptm).


### Ppsm {#Ppsm}
```
public static final PresentationFileType Ppsm
```


Τα αρχεία με επέκταση PPSM αντιπροσωπεύουν μορφή αρχείου Slide Show με ενεργοποιημένα Macros που δημιουργήθηκε με το Microsoft PowerPoint 2007 ή νεότερες εκδόσεις.
Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/presentation/ppsm).


### Fodp {#Fodp}
```
public static final PresentationFileType Fodp
```


Τα αρχεία με την επέκταση FODP αντιπροσωπεύουν Παρουσίαση OpenDocument Flat XML. Το αρχείο παρουσίασης αποθηκεύεται σε μορφή OpenDocument, αλλά χρησιμοποιεί μορφή επίπεδου XML αντί για το .ZIP κοντέινερ που χρησιμοποιείται από τα τυπικά αρχεία .ODP.


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
