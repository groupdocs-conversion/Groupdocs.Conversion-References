---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει έγγραφα Diagram. Περιλαμβάνει τους ακόλουθους τύπους Drawio./diagramfiletype/drawio Mmd./diagramfiletype/mmd Vdw./diagramfiletype/vdw Vdx./diagramfiletype/vdx Vsd./diagramfiletype/vsd Vsdm./diagramfiletype/vsdm Vsdx./diagramfiletype/vsdx Vss./diagramfiletype/vss Vssm./diagramfiletype/vssm Vssx./diagramfiletype/vssx Vst./diagramfiletype/vst Vstm./diagramfiletype/vstm Vstx./diagramfiletype/vstx Vsx./diagramfiletype/vsx Vtx./diagramfiletype/vtx."
type: docs
weight: 1100
url: /el/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Ορίζει έγγραφα Diagram. Περιλαμβάνει τους ακόλουθους τύπους: [`Drawio`](./drawio), [`Mmd`](./mmd), [`Vdw`](./vdw), [`Vdx`](./vdx), [`Vsd`](./vsd), [`Vsdm`](./vsdm), [`Vsdx`](./vsdx), [`Vss`](./vss), [`Vssm`](./vssm), [`Vssx`](./vssx), [`Vst`](./vst), [`Vstm`](./vstm), [`Vstx`](./vstx), [`Vsx`](./vsx), [`Vtx`](./vtx).

```csharp
public sealed class DiagramFileType : FileType
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Κατασκευαστής σειριοποίησης |

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
| static readonly [Drawio](../../groupdocs.conversion.filetypes/diagramfiletype/drawio) | Ένα αρχείο με επέκταση DRAWIO είναι ένα διάγραμμα που δημιουργήθηκε με το diagrams.net (παλαιότερα draw.io). Αποθηκεύεται σε μορφότυπο αρχείου XML με το στοιχείο ρίζας mxfile και περιέχει το περιεχόμενο και τη μορφοποίηση των στοιχείων του διαγράμματος όπως κείμενο, εικόνες, διάταξη, σχήματα και τοποθέτηση. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://wiki.fileformat.com/web/drawio). |
| static readonly [Mmd](../../groupdocs.conversion.filetypes/diagramfiletype/mmd) | Ένα αρχείο με επέκταση MMD είναι ένα διάγραμμα γραμμένο στη γλώσσα σήμανσης Mermaid. Αποθηκεύεται ως απλό κείμενο που ξεκινά με τη δήλωση του διαγράμματος, όπως flowchart ή sequenceDiagram, ακολουθούμενο από τον ορισμό των κόμβων και των συνδέσεων μεταξύ τους. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://mermaid.js.org/intro/). |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | Το VDW είναι το μορφότυπο αρχείου Visio Graphics Service που καθορίζει τα ρεύματα και τις αποθηκεύσεις που απαιτούνται για την απόδοση ενός σχεδίου Web. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://wiki.fileformat.com/web/vdw). |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Οποιοδήποτε σχέδιο ή διάγραμμα δημιουργείται στο Microsoft Visio, αλλά αποθηκεύεται σε μορφή XML, έχει επέκταση .VDX. Ένα αρχείο Visio XML δημιουργείται στο λογισμικό Visio, το οποίο αναπτύσσεται από τη Microsoft. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://wiki.fileformat.com/image/vdx). |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | Τα αρχεία VSD είναι σχέδια που δημιουργούνται με την εφαρμογή Microsoft Visio για την αναπαράσταση ποικιλίας γραφικών αντικειμένων και της διασύνδεσής τους. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://wiki.fileformat.com/image/vsd). |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | Τα αρχεία με επέκταση VSDM είναι αρχεία σχεδίασης που δημιουργούνται με την εφαρμογή Microsoft Visio και υποστηρίζουν μακροεντολές. Τα αρχεία VSDM είναι σχέδια OPC/XML που είναι παρόμοια με τα VSDX, αλλά παρέχουν επίσης τη δυνατότητα εκτέλεσης μακροεντολών όταν το αρχείο ανοίγει. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vsdm). |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | Τα αρχεία με επέκταση .VSDX αντιπροσωπεύουν τη μορφή αρχείου Microsoft Visio που εισήχθη από το Microsoft Office 2013 και μετά. Αναπτύχθηκε για να αντικαταστήσει τη δυαδική μορφή αρχείου .VSD, η οποία υποστηρίζεται από παλαιότερες εκδόσεις του Microsoft Visio. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vsdx). |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | Τα VSS είναι αρχεία στενσίλ που δημιουργήθηκαν με το Microsoft Visio 2007 και παλαιότερα. Τα αρχεία στενσίλ παρέχουν αντικείμενα σχεδίασης που μπορούν να συμπεριληφθούν σε ένα σχέδιο Visio .VSD. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vss). |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | Τα αρχεία με επέκταση .VSSM είναι αρχεία στενσίλ Microsoft Visio που παρέχουν υποστήριξη για μακροεντολές. Ένα αρχείο VSSM όταν ανοίγει επιτρέπει την εκτέλεση των μακροεντολών για την επίτευξη της επιθυμητής μορφοποίησης και τοποθέτησης των σχημάτων σε ένα διάγραμμα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vssm). |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | Τα αρχεία με επέκταση .VSSX είναι στενσίλ σχεδίασης που δημιουργήθηκαν με το Microsoft Visio 2013 και νεότερα. Η μορφή αρχείου VSSX μπορεί να ανοιχτεί με το Visio 2013 και νεότερα. Τα αρχεία Visio είναι γνωστά για την αναπαράσταση μιας ποικιλίας στοιχείων σχεδίασης όπως συλλογή σχημάτων, συνδέσμων, διαγραμμάτων ροής, διάταξης δικτύου, διαγραμμάτων UML. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | Τα αρχεία με επέκταση VST είναι αρχεία διανυσματικών εικόνων που δημιουργούνται με το Microsoft Visio και λειτουργούν ως πρότυπα για τη δημιουργία περαιτέρω αρχείων. Αυτά τα πρότυπα αρχεία είναι σε δυαδική μορφή αρχείου και περιέχουν την προεπιλεγμένη διάταξη και ρυθμίσεις που χρησιμοποιούνται για τη δημιουργία νέων σχεδίων Visio. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | Τα αρχεία με επέκταση VSTM είναι πρότυπα αρχεία που δημιουργούνται με το Microsoft Visio και υποστηρίζουν μακροεντολές. Σε αντίθεση με τα αρχεία VSDX, τα αρχεία που δημιουργούνται από πρότυπα VSTM μπορούν να εκτελούν μακροεντολές που έχουν αναπτυχθεί σε κώδικα Visual Basic for Applications (VBA). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | Τα αρχεία με επέκταση VSTX είναι πρότυπα αρχεία σχεδίασης που δημιουργήθηκαν με το Microsoft Visio 2013 και νεότερα. Αυτά τα αρχεία VSTX παρέχουν ένα σημείο εκκίνησης για τη δημιουργία σχεδίων Visio, αποθηκευμένα ως αρχεία .VSDX, με προεπιλεγμένη διάταξη και ρυθμίσεις. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | Τα αρχεία με επέκταση .VSX αναφέρονται σε στενσίλ που αποτελούνται από σχέδια και σχήματα που χρησιμοποιούνται για τη δημιουργία διαγραμμάτων στο Microsoft Visio. Τα αρχεία VSX αποθηκεύονται σε μορφή XML και υποστηρίζονταν μέχρι το Visio 2013. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | Ένα αρχείο με επέκταση VTX είναι πρότυπο σχεδίου Microsoft Visio που αποθηκεύεται στο δίσκο σε μορφή XML. Το πρότυπο στοχεύει να παρέχει ένα αρχείο με βασικές ρυθμίσεις που μπορούν να χρησιμοποιηθούν για τη δημιουργία πολλαπλών αρχείων Visio με τις ίδιες ρυθμίσεις. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/image/vtx). |

### Δείτε επίσης

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
