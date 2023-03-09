---
title: PresentationFileType
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Καθορίζει μορφές αρχείων παρουσίασης που αποθηκεύουν συλλογή εγγραφών για την υποδοχή δεδομένων παρουσίασης όπως διαφάνειες σχήματα κείμενο κινούμενα σχέδια βίντεο ήχο και ενσωματωμένα αντικείμενα. Περιλαμβάνει τους ακόλουθους τύπους αρχείων Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . Μάθετε περισσότερα σχετικά με τις μορφές παρουσίασηςεδώhttps//wiki.fileformat.com/presentation .
type: docs
weight: 1020
url: /el/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Καθορίζει μορφές αρχείων παρουσίασης που αποθηκεύουν συλλογή εγγραφών για την υποδοχή δεδομένων παρουσίασης, όπως διαφάνειες, σχήματα, κείμενο, κινούμενα σχέδια, βίντεο, ήχο και ενσωματωμένα αντικείμενα. Περιλαμβάνει τους ακόλουθους τύπους αρχείων: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Pptm`](./pptm) , [`Pptx`](./pptx) . Μάθετε περισσότερα σχετικά με τις μορφές παρουσίασης[εδώ](https://wiki.fileformat.com/presentation) .

```csharp
public sealed class PresentationFileType : FileType
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Κατασκευαστής σειριοποίησης |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | Τα αρχεία με επέκταση FODP αντιπροσωπεύουν την Επίπεδη παρουσίαση XML OpenDocument. Το αρχείο παρουσίασης αποθηκεύτηκε σε μορφή OpenDocument, αλλά αποθηκεύτηκε χρησιμοποιώντας μια επίπεδη μορφή XML αντί για το κοντέινερ .ZIP που χρησιμοποιείται από τα τυπικά αρχεία .ODP |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | Τα αρχεία με επέκταση ODP αντιπροσωπεύουν τη μορφή αρχείου παρουσίασης που χρησιμοποιείται από το OpenOffice.org στο πρότυπο OASISOpen. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | Τα αρχεία με επέκταση .OTP αντιπροσωπεύουν αρχεία προτύπων παρουσίασης που δημιουργούνται από εφαρμογές σε τυπική μορφή OASIS OpenDocument. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | Τα αρχεία με επέκταση .POT αντιπροσωπεύουν αρχεία προτύπων του Microsoft PowerPoint που δημιουργήθηκαν από τις εκδόσεις του PowerPoint 97-2003. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | Τα αρχεία με επέκταση POTM είναι αρχεία προτύπων του Microsoft PowerPoint με υποστήριξη για μακροεντολές. Τα αρχεία POTM δημιουργούνται με PowerPoint 2007 ή νεότερη έκδοση και περιέχουν προεπιλεγμένες ρυθμίσεις που μπορούν να χρησιμοποιηθούν για τη δημιουργία περαιτέρω αρχείων παρουσίασης. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | Τα αρχεία με επέκταση .POTX αντιπροσωπεύουν παρουσιάσεις προτύπων Microsoft PowerPoint που δημιουργούνται με το Microsoft PowerPoint 2007 και νεότερη έκδοση. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint Slide Show, τα αρχεία δημιουργούνται χρησιμοποιώντας το Microsoft PowerPoint για σκοπούς προβολής διαφανειών. Η ανάγνωση και η δημιουργία αρχείων PPS υποστηρίζεται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | Τα αρχεία με επέκταση PPSM αντιπροσωπεύουν τη μορφή αρχείου Slide Show με δυνατότητα μακροεντολής που δημιουργήθηκε με Microsoft PowerPoint 2007 ή νεότερη έκδοση. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | Το αρχείο PPSX, Power Point Slide Show, δημιουργείται με χρήση του Microsoft PowerPoint 2007 και νεότερο για σκοπούς προβολής διαφανειών. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | Ένα αρχείο με επέκταση PPT αντιπροσωπεύει το αρχείο PowerPoint που αποτελείται από μια συλλογή διαφανειών για εμφάνιση ως Παρουσίαση. Καθορίζει τη μορφή δυαδικού αρχείου που χρησιμοποιείται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | Τα αρχεία με επέκταση PPTM είναι αρχεία παρουσίασης με δυνατότητα μακροεντολής που δημιουργούνται με Microsoft PowerPoint 2007 ή νεότερες εκδόσεις. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | Τα αρχεία με επέκταση PPTX είναι αρχεία παρουσίασης που δημιουργήθηκαν με τη δημοφιλή εφαρμογή Microsoft PowerPoint. Σε αντίθεση με την προηγούμενη έκδοση της μορφής αρχείου παρουσίασης PPT που ήταν δυαδική, η μορφή PPTX βασίζεται στη μορφή αρχείου παρουσίασης ανοιχτής XML του Microsoft PowerPoint. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/pptx) . |

### Δείτε επίσης

* class [FileType](../filetype)
* χώρος ονομάτων [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* συνέλευση [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
