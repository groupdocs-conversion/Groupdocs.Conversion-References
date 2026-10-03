---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει μορφές αρχείων Παρουσίασης που αποθηκεύουν συλλογή εγγραφών για να φιλοξενήσουν δεδομένα παρουσίασης όπως διαφάνειες, σχήματα, κείμενο, κινούμενα σχέδια, βίντεο, ήχο και ενσωματωμένα αντικείμενα. Περιλαμβάνει τους ακόλουθους τύπους αρχείων Odp./presentationfiletype/odp Otp./presentationfiletype/otp Pot./presentationfiletype/pot Potm./presentationfiletype/potm Potx./presentationfiletype/potx Pps./presentationfiletype/pps Ppsm./presentationfiletype/ppsm Ppsx./presentationfiletype/ppsx Ppt./presentationfiletype/ppt Pptm./presentationfiletype/pptm Pptx./presentationfiletype/pptx. Μάθετε περισσότερα για τις μορφές Παρουσίασης εδώhttps//wiki.fileformat.com/presentation."
type: docs
weight: 1210
url: /el/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Ορίζει μορφές αρχείων Παρουσίασης που αποθηκεύουν συλλογή εγγραφών για να φιλοξενήσουν δεδομένα παρουσίασης όπως διαφάνειες, σχήματα, κείμενο, κινούμενα σχέδια, βίντεο, ήχο και ενσωματωμένα αντικείμενα. Περιλαμβάνει τους ακόλουθους τύπους αρχείων: [`Odp`](./odp), [`Otp`](./otp), [`Pot`](./pot), [`Potm`](./potm), [`Potx`](./potx), [`Pps`](./pps), [`Ppsm`](./ppsm), [`Ppsx`](./ppsx), [`Ppt`](./ppt), [`Pptm`](./pptm), [`Pptx`](./pptx). Μάθετε περισσότερα για τις μορφές Παρουσίασης [εδώ](https://wiki.fileformat.com/presentation).

```csharp
public sealed class PresentationFileType : FileType
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Κατασκευαστής σειριοποίησης |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | Τα αρχεία με επέκταση FODP αντιπροσωπεύουν Παρουσίαση OpenDocument Flat XML. Το αρχείο παρουσίασης αποθηκεύεται σε μορφή OpenDocument, αλλά χρησιμοποιεί μορφή Flat XML αντί για το .ZIP κοντέινερ που χρησιμοποιείται από τα τυπικά αρχεία .ODP. |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | Τα αρχεία με επέκταση ODP αντιπροσωπεύουν μορφή αρχείου παρουσίασης που χρησιμοποιείται από το OpenOffice.org στο πρότυπο OASISOpen. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | Τα αρχεία με επέκταση .OTP αντιπροσωπεύουν αρχεία προτύπων παρουσίασης που δημιουργούνται από εφαρμογές σε μορφή προτύπου OASIS OpenDocument. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | Τα αρχεία με επέκταση .POT αντιπροσωπεύουν αρχεία προτύπων Microsoft PowerPoint που δημιουργήθηκαν από εκδόσεις PowerPoint 97-2003. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | Τα αρχεία με επέκταση POTM είναι αρχεία προτύπων Microsoft PowerPoint με υποστήριξη Μακροεντολών. Τα αρχεία POTM δημιουργούνται με PowerPoint 2007 ή νεότερο και περιέχουν προεπιλεγμένες ρυθμίσεις που μπορούν να χρησιμοποιηθούν για τη δημιουργία περαιτέρω αρχείων παρουσίασης. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | Τα αρχεία με επέκταση .POTX αντιπροσωπεύουν προτυπικές παρουσιάσεις Microsoft PowerPoint που δημιουργούνται με Microsoft PowerPoint 2007 και νεότερο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | Τα αρχεία PPS, PowerPoint Slide Show, δημιουργούνται χρησιμοποιώντας το Microsoft PowerPoint για σκοπό παρουσίασης διαφάνειας. Η ανάγνωση και δημιουργία αρχείων PPS υποστηρίζεται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | Τα αρχεία με επέκταση PPSM αντιπροσωπεύουν μορφή αρχείου Slide Show με ενεργοποιημένες Μακροεντολές, δημιουργημένη με Microsoft PowerPoint 2007 ή νεότερο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | Τα αρχεία PPSX, Power Point Slide Show, δημιουργούνται χρησιμοποιώντας το Microsoft PowerPoint 2007 και νεότερο για σκοπό παρουσίασης διαφάνειας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | Ένα αρχείο με επέκταση PPT αντιπροσωπεύει αρχείο PowerPoint που αποτελείται από μια συλλογή διαφανειών για προβολή ως SlideShow. Καθορίζει τη Δυαδική Μορφή Αρχείου που χρησιμοποιείται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | Τα αρχεία με επέκταση PPTM είναι αρχεία Παρουσίασης με ενεργοποιημένες Μακροεντολές που δημιουργούνται με Microsoft PowerPoint 2007 ή νεότερες εκδόσεις. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | Τα αρχεία με επέκταση PPTX είναι αρχεία παρουσίασης που δημιουργούνται με τη δημοφιλής εφαρμογή Microsoft PowerPoint. Σε αντίθεση με την προηγούμενη έκδοση του μορφότυπου αρχείου παρουσίασης PPT που ήταν δυαδική, η μορφή PPTX βασίζεται στον ανοιχτό XML μορφότυπο παρουσίασης του Microsoft PowerPoint. Μάθετε περισσότερα για αυτόν τον μορφότυπο αρχείου [εδώ](https://wiki.fileformat.com/presentation/pptx). |

### Δείτε επίσης

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
