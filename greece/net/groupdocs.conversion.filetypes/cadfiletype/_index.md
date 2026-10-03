---
title: "CadFileType"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει έγγραφα CAD (Computer Aided Design) που χρησιμοποιούνται για μορφές αρχείων 3D γραφικών και μπορεί να περιέχουν σχεδιασμούς 2D ή 3D. Περιλαμβάνει τους ακόλουθους τύπους Cf2./cadfiletype/cf2 Dgn./cadfiletype/dgn Dwf./cadfiletype/dwf Dwfx./cadfiletype/dwfx Dwg./cadfiletype/dwg Dwt./cadfiletype/dwt Dxf./cadfiletype/dxf Ifc./cadfiletype/ifc Igs./cadfiletype/igs Plt./cadfiletype/plt Stl./cadfiletype/stl. Μάθετε περισσότερα για τις μορφές CAD εδώhttps//wiki.fileformat.com/cad."
type: docs
weight: 1070
url: /el/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Ορίζει έγγραφα CAD (Computer Aided Design) που χρησιμοποιούνται για μορφές αρχείων 3D γραφικών και μπορεί να περιέχουν σχεδιασμούς 2D ή 3D. Περιλαμβάνει τους ακόλουθους τύπους: [`Cf2`](./cf2)[`Dgn`](./dgn), [`Dwf`](./dwf), [`Dwfx`](./dwfx)[`Dwg`](./dwg), [`Dwt`](./dwt), [`Dxf`](./dxf), [`Ifc`](./ifc), [`Igs`](./igs), [`Plt`](./plt), [`Stl`](./stl). Μάθετε περισσότερα για τις μορφές CAD [εδώ](https://wiki.fileformat.com/cad).

```csharp
public sealed class CadFileType : FileType
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [CadFileType](cadfiletype)() | Κατασκευαστής σειριοποίησης |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Περιγραφή τύπου αρχείου |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Η επέκταση αρχείου |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Η οικογένεια αρχείου |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Η μορφή αρχείου |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Συγκρίνει το τρέχον αντικείμενο με άλλο. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Υλοποιεί [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Αναπαράσταση συμβολοσειράς |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Κοινό αρχείο μορφής αρχείου. Αρχείο CAD που περιέχει σχεδιασμούς πακέτων 3D ή άλλα δεδομένα μοντέλου· μπορεί να επεξεργαστεί και να κοπεί από μηχανή CAD/CAM, όπως μια συσκευή κοπής. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | Τα αρχεία DGN, Design, είναι σχέδια που δημιουργούνται και υποστηρίζονται από εφαρμογές CAD όπως το MicroStation και το Intergraph Interactive Graphics Design System. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/cad/dgn). |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Το Design Web Format (DWF) αντιπροσωπεύει σχέδιο 2D/3D σε συμπιεσμένη μορφή για προβολή, ανασκόπηση ή εκτύπωση αρχείων σχεδίου. Περιέχει γραφικά και κείμενο ως μέρος των δεδομένων σχεδίου και μειώνει το μέγεθος του αρχείου λόγω της συμπιεσμένης μορφής του. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/cad/dwf). |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | Το αρχείο DWFX είναι ένα 2D ή 3D σχέδιο που δημιουργείται με το λογισμικό Autodesk CAD. Αποθηκεύεται στη μορφή DWFx, η οποία είναι παρόμοια με ένα αρχείο .DWF, αλλά μορφοποιείται χρησιμοποιώντας το XML Paper Specification (XPS) της Microsoft. |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | Τα αρχεία με επέκταση DWG αντιπροσωπεύουν ιδιόκτητα δυαδικά αρχεία που χρησιμοποιούνται για την αποθήκευση δεδομένων σχεδίασης 2D και 3D. Όπως τα DXF, που είναι αρχεία ASCII, τα DWG αντιπροσωπεύουν τη δυαδική μορφή αρχείου για σχέδια CAD (Computer Aided Design). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/cad/dwg). |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | Ένα αρχείο DWT είναι ένα πρότυπο σχεδίου AutoCAD που χρησιμοποιείται ως εκκίνηση για τη δημιουργία σχεδίων που μπορούν να αποθηκευτούν ως αρχεία DWG. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/cad/dwt). |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | Το DXF, Drawing Interchange Format ή Drawing Exchange Format, είναι μια ετικετοποιημένη αναπαράσταση δεδομένων αρχείου σχεδίου AutoCAD. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/cad/dxf). |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | Τα αρχεία με επέκταση IFC αναφέρονται στη μορφή αρχείου Industry Foundation Classes (IFC) που καθιερώνει διεθνή πρότυπα για την εισαγωγή και εξαγωγή αντικειμένων κτιρίων και των ιδιοτήτων τους. Αυτή η μορφή αρχείου παρέχει διαλειτουργικότητα μεταξύ διαφορετικών εφαρμογών λογισμικού. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/cad/ifc). |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Μορφή εγγράφου Igs |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | Η μορφή αρχείου PLT είναι ένα διανυσματικό αρχείο plotter που εισήχθη από την Autodesk, Inc. και περιέχει πληροφορίες για ένα συγκεκριμένο αρχείο CAD. Οι λεπτομέρειες εκτύπωσης απαιτούν ακρίβεια και προσοχή στην παραγωγή, και η χρήση του αρχείου PLT το εγγυάται, καθώς όλες οι εικόνες εκτυπώνονται με γραμμές αντί για κουκκίδες. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/cad/plt). |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | Το STL, συντομογραφία για stereolithrography, είναι μια εναλλάξιμη μορφή αρχείου που αντιπροσωπεύει γεωμετρία επιφάνειας τριών διαστάσεων. Η μορφή αρχείου αυτή χρησιμοποιείται σε πολλούς τομείς όπως η γρήγορη πρωτοτυποποίηση, η 3D εκτύπωση και η υποβοηθούμενη κατασκευή. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/cad/stl). |

### Δείτε επίσης

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
