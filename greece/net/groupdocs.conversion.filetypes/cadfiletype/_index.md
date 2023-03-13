---
title: CadFileType
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Καθορίζει έγγραφα CAD Computer Aided Design που χρησιμοποιούνται για μορφές αρχείων τρισδιάστατων γραφικών και μπορεί να περιέχουν σχέδια 2D ή 3D. Περιλαμβάνει τους ακόλουθους τύπους Cf2./cadfiletype/cf2Dgn./cadfiletype/dgn  Dwf./cadfiletype/dwf  Dwfx./cadfiletype/dwfxDwg./cadfiletype/dwg  Dwt./cadfiletype/dwt  Dxf./cadfiletype/dxf  Ifc./cadfiletype/ifc  Igs./cadfiletype/igs  Plt./cadfiletype/plt  Stl./cadfiletype/stl . Μάθετε περισσότερα σχετικά με τις μορφές CADεδώhttps//wiki.fileformat.com/cad .
type: docs
weight: 860
url: /el/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Καθορίζει έγγραφα CAD (Computer Aided Design) που χρησιμοποιούνται για μορφές αρχείων τρισδιάστατων γραφικών και μπορεί να περιέχουν σχέδια 2D ή 3D. Περιλαμβάνει τους ακόλουθους τύπους: [`Cf2`](./cf2)[`Dgn`](./dgn) , [`Dwf`](./dwf) , [`Dwfx`](./dwfx)[`Dwg`](./dwg) , [`Dwt`](./dwt) , [`Dxf`](./dxf) , [`Ifc`](./ifc) , [`Igs`](./igs) , [`Plt`](./plt) , [`Stl`](./stl) . Μάθετε περισσότερα σχετικά με τις μορφές CAD[εδώ](https://wiki.fileformat.com/cad) .

```csharp
public sealed class CadFileType : FileType
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [CadFileType](cadfiletype)() | Κατασκευαστής σειριοποίησης |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Περιγραφή τύπου αρχείου |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Η επέκταση αρχείου |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Η οικογένεια αρχείων |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Η μορφή αρχείου |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Συγκρίνει το τρέχον αντικείμενο με άλλο. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Εξυπηρετεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Αναπαράσταση συμβολοσειράς |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Αρχείο κοινής μορφής αρχείου. Αρχείο CAD που περιέχει τρισδιάστατα σχέδια πακέτων ή άλλα δεδομένα μοντέλου. μπορεί να υποβληθεί σε επεξεργασία και κοπή από μηχανή CAD/CAM, όπως συσκευή κοπής με μήτρα. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN, Design, τα αρχεία είναι σχέδια που δημιουργούνται από και υποστηρίζονται από εφαρμογές CAD όπως το MicroStation και το Intergraph Interactive Graphics Design System. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/cad/dgn) . |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Το Design Web Format (DWF) αντιπροσωπεύει ένα σχέδιο 2D/3D σε συμπιεσμένη μορφή για προβολή, αναθεώρηση ή εκτύπωση αρχείων σχεδίασης. Περιέχει γραφικά και κείμενο ως μέρος των δεδομένων σχεδίασης και μειώνει το μέγεθος του αρχείου λόγω της συμπιεσμένης μορφής του. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/cad/dwf) . |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | Το αρχείο DWFX είναι ένα σχέδιο 2D ή 3D που δημιουργήθηκε με το λογισμικό Autodesk CAD. Αποθηκεύεται σε μορφή DWFx, η οποία είναι παρόμοια με ένα . αρχείο DWF, αλλά έχει μορφοποιηθεί με χρήση της προδιαγραφής χαρτιού XML της Microsoft (XPS). |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | Τα αρχεία με επέκταση DWG αντιπροσωπεύουν ιδιόκτητα δυαδικά αρχεία που χρησιμοποιούνται για να περιέχουν δεδομένα σχεδίασης 2D και 3D. Όπως το DXF, που είναι αρχεία ASCII, το DWG αντιπροσωπεύει τη μορφή δυαδικού αρχείου για σχέδια CAD (Computer Aided Design). Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/cad/dwg) . |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | Ένα αρχείο DWT είναι ένα αρχείο προτύπου σχεδίασης AutoCAD που χρησιμοποιείται ως εκκίνηση για τη δημιουργία σχεδίων που μπορούν να αποθηκευτούν ως αρχεία DWG. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/cad/dwt) . |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | Το DXF, Drawing Interchange Format ή Drawing Exchange Format, είναι μια αναπαράσταση δεδομένων με ετικέτα του αρχείου σχεδίασης AutoCAD. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/cad/dxf) . |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | Τα αρχεία με επέκταση IFC αναφέρονται στη μορφή αρχείου Industry Foundation Classes (IFC) που θεσπίζει διεθνή πρότυπα για την εισαγωγή και εξαγωγή αντικειμένων κτιρίου και των ιδιοτήτων τους. Αυτή η μορφή αρχείου παρέχει διαλειτουργικότητα μεταξύ διαφορετικών εφαρμογών λογισμικού. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/cad/ifc) . |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Μορφή εγγράφου Igs |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | Η μορφή αρχείου PLT είναι ένα διανυσματικό αρχείο plotter που εισήχθη από την Autodesk, Inc. και περιέχει πληροφορίες για ένα συγκεκριμένο αρχείο CAD. Οι λεπτομέρειες σχεδίασης απαιτούν ακρίβεια και ακρίβεια στην παραγωγή και η χρήση του αρχείου PLT εγγυάται αυτό, καθώς όλες οι εικόνες εκτυπώνονται χρησιμοποιώντας γραμμές αντί για τελείες. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/cad/plt) . |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | Το STL, συντομογραφία για τη στερεολιθρογραφία, είναι μια εναλλάξιμη μορφή αρχείου που αντιπροσωπεύει τρισδιάστατη γεωμετρία επιφάνειας. Η μορφή αρχείου βρίσκει τη χρήση της σε πολλά πεδία, όπως η γρήγορη δημιουργία πρωτοτύπων, η τρισδιάστατη εκτύπωση και η κατασκευή με τη βοήθεια υπολογιστή. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/cad/stl) . |

### Δείτε επίσης

* class [FileType](../filetype)
* χώρος ονομάτων [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* συνέλευση [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
