---
title: "CadFileType"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ορίζει έγγραφα CAD (Computer Aided Design) που χρησιμοποιούνται για μορφές αρχείων 3D γραφικών και μπορεί να περιέχουν σχέδια 2D ή 3D."
type: docs
weight: 11
url: /el/java/com.groupdocs.conversion.filetypes/cadfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadFileType extends FileType implements Serializable
```

Ορίζει έγγραφα CAD (Computer Aided Design) που χρησιμοποιούνται για μορφές αρχείων 3D γραφικών και μπορεί να περιέχουν σχεδιασμούς 2D ή 3D.
Περιλαμβάνει τους ακόλουθους τύπους:
[Dgn](../../com.groupdocs.conversion.filetypes/cadfiletype#Dgn),
[Dwf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwf),
[Dwg](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwg),
[Dwt](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwt),
[Dxf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dxf),
[Ifc](../../com.groupdocs.conversion.filetypes/cadfiletype#Ifc),
[Igs](../../com.groupdocs.conversion.filetypes/cadfiletype#Igs),
[Plt](../../com.groupdocs.conversion.filetypes/cadfiletype#Plt),
[Stl](../../com.groupdocs.conversion.filetypes/cadfiletype#Stl).
[Cf2](../../com.groupdocs.conversion.filetypes/cadfiletype#Cf2).
[Dwfx](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwfx).
Μάθετε περισσότερα για τις μορφές CAD [εδώ](../https://wiki.fileformat.com/cad).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [CadFileType()](#CadFileType--) | Κατασκευαστής σειριοποίησης |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Dxf](#Dxf) | Το DXF (Drawing Interchange Format ή Drawing Exchange Format) είναι μια ετικετοποιημένη αναπαράσταση δεδομένων αρχείου σχεδίου AutoCAD. |
|
|  | [Dwg](#Dwg) | Τα αρχεία με επέκταση DWG αντιπροσωπεύουν ιδιόκτητα δυαδικά αρχεία που χρησιμοποιούνται για την αποθήκευση δεδομένων σχεδίου 2D και 3D. |
|
|  | [Dgn](#Dgn) | Τα αρχεία DGN (Design) είναι σχέδια που δημιουργούνται και υποστηρίζονται από εφαρμογές CAD όπως το MicroStation και το Intergraph Interactive Graphics Design System. |
|
|  | [Dwf](#Dwf) | Το Design Web Format (DWF) αντιπροσωπεύει σχέδια 2D/3D σε συμπιεσμένη μορφή για προβολή, ανασκόπηση ή εκτύπωση αρχείων σχεδίου. |
|
|  | [Stl](#Stl) | Το STL, συντομογραφία για stereolithrography, είναι μια εναλλάξιμη μορφή αρχείου που αντιπροσωπεύει γεωμετρία επιφάνειας τριών διαστάσεων. |
|
|  | [Ifc](#Ifc) | Τα αρχεία με επέκταση IFC αναφέρονται στη μορφή αρχείου Industry Foundation Classes (IFC) που καθιερώνει διεθνή πρότυπα για την εισαγωγή και εξαγωγή αντικειμένων κτιρίων και των ιδιοτήτων τους. |
|
|  | [Plt](#Plt) | Η μορφή αρχείου PLT είναι ένα διανυσματικό αρχείο σχεδιαστή που εισήχθη από την Autodesk, Inc. |
|
|  | [Igs](#Igs) | Μορφή εγγράφου Igs |
|
|  | [Dwt](#Dwt) | Ένα αρχείο DWT είναι ένα πρότυπο σχεδίου AutoCAD που χρησιμοποιείται ως βάση για τη δημιουργία σχεδίων που μπορούν να αποθηκευτούν ως αρχεία DWG. |
|
|  | [Dwfx](#Dwfx) | Το αρχείο DWFX είναι ένα σχέδιο 2D ή 3D που δημιουργήθηκε με λογισμικό Autodesk CAD. |
|
|  | [Cf2](#Cf2) | Αρχείο Κοινής Μορφής (Common File Format). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### CadFileType() {#CadFileType--}
```
public CadFileType()
```


Κατασκευαστής σειριοποίησης


### Dxf {#Dxf}
```
public static final CadFileType Dxf
```


Το DXF (Drawing Interchange Format ή Drawing Exchange Format) είναι μια ετικετοποιημένη αναπαράσταση δεδομένων αρχείου σχεδίου AutoCAD.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/cad/dxf).


### Dwg {#Dwg}
```
public static final CadFileType Dwg
```


Τα αρχεία με επέκταση DWG αντιπροσωπεύουν ιδιόκτητα δυαδικά αρχεία που χρησιμοποιούνται για την αποθήκευση δεδομένων σχεδίου 2D και 3D. Όπως το DXF, που είναι αρχεία ASCII, το DWG αντιπροσωπεύει τη δυαδική μορφή αρχείου για σχέδια CAD (Computer Aided Design).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/cad/dwg)


### Dgn {#Dgn}
```
public static final CadFileType Dgn
```


Τα αρχεία DGN (Design) είναι σχέδια που δημιουργούνται και υποστηρίζονται από εφαρμογές CAD όπως το MicroStation και το Intergraph Interactive Graphics Design System.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/cad/dgn).


### Dwf {#Dwf}
```
public static final CadFileType Dwf
```


Το Design Web Format (DWF) αντιπροσωπεύει σχέδια 2D/3D σε συμπιεσμένη μορφή για προβολή, ανασκόπηση ή εκτύπωση αρχείων σχεδίου. Περιέχει γραφικά και κείμενο ως μέρος των δεδομένων σχεδίου και μειώνει το μέγεθος του αρχείου λόγω της συμπιεσμένης μορφής του.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://wiki.fileformat.com/cad/dwf).


### Stl {#Stl}
```
public static final CadFileType Stl
```


STL, συντομογραφία για stereolithrography, είναι ένα εναλλάξιμο μορφότυπο αρχείου που αντιπροσωπεύει γεωμετρία επιφάνειας τριών διαστάσεων. Ο μορφότυπος αρχείου χρησιμοποιείται σε διάφορους τομείς όπως η γρήγορη πρωτοτυποποίηση, η 3D εκτύπωση και η υποβοηθούμενη από υπολογιστή κατασκευή.
Μάθετε περισσότερα για αυτόν τον μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/cad/stl).


### Ifc {#Ifc}
```
public static final CadFileType Ifc
```


Αρχεία με επέκταση IFC αναφέρονται στο μορφότυπο αρχείου Industry Foundation Classes (IFC) που καθιερώνει διεθνή πρότυπα για την εισαγωγή και εξαγωγή αντικειμένων κτιρίων και των ιδιοτήτων τους. Αυτός ο μορφότυπος αρχείου παρέχει διαλειτουργικότητα μεταξύ διαφορετικών εφαρμογών λογισμικού.
Μάθετε περισσότερα για αυτόν τον μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/cad/ifc).


### Plt {#Plt}
```
public static final CadFileType Plt
```


Ο μορφότυπος αρχείου PLT είναι ένα αρχείο διαγράμματος βάσει διανυσματικού plotter που εισήχθη από την Autodesk, Inc. και περιέχει πληροφορίες για ένα συγκεκριμένο αρχείο CAD. Οι λεπτομέρειες σχεδίασης απαιτούν ακρίβεια και προσοχή στην παραγωγή, και η χρήση του αρχείου PLT εγγυάται αυτό καθώς όλες οι εικόνες εκτυπώνονται με γραμμές αντί για κουκκίδες.
Μάθετε περισσότερα για αυτόν τον μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/cad/plt).


### Igs {#Igs}
```
public static final CadFileType Igs
```


Μορφή εγγράφου Igs


### Dwt {#Dwt}
```
public static final CadFileType Dwt
```


Ένα αρχείο DWT είναι ένα πρότυπο σχεδίου AutoCAD που χρησιμοποιείται ως βάση για τη δημιουργία σχεδίων που μπορούν να αποθηκευτούν ως αρχεία DWG.
Μάθετε περισσότερα για αυτόν τον μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/cad/dwt).


### Dwfx {#Dwfx}
```
public static final CadFileType Dwfx
```


Το αρχείο DWFX είναι ένα σχέδιο 2D ή 3D που δημιουργήθηκε με λογισμικό Autodesk CAD. Αποθηκεύεται σε μορφότυπο DWFx, ο οποίος είναι παρόμοιος με ένα αρχείο .DWF, αλλά μορφοποιείται χρησιμοποιώντας το XML Paper Specification (XPS) της Microsoft.


### Cf2 {#Cf2}
```
public static final CadFileType Cf2
```


Κοινό Μορφότυπο Αρχείου. Αρχείο CAD που περιέχει σχεδιασμούς πακέτων 3D ή άλλα δεδομένα μοντέλου· μπορεί να επεξεργαστεί και να κοπεί από μηχάνημα CAD/CAM, όπως μια συσκευή κοπής χαρτιού.


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
