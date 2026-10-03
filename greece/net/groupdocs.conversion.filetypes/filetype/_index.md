---
title: "FileType"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Βασική κλάση τύπου αρχείου"
type: docs
weight: 1130
url: /el/net/groupdocs.conversion.filetypes/filetype/
---
## FileType class

Βασική κλάση τύπου αρχείου

```csharp
public class FileType : Enumeration
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [FileType](filetype)() | Κατασκευαστής σειριοποίησης |

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
| static [FromExtension](../../groupdocs.conversion.filetypes/filetype/fromextension)(string) | Λαμβάνει το FileType για την παρεχόμενη επέκταση αρχείου |
| static [FromFilename](../../groupdocs.conversion.filetypes/filetype/fromfilename)(string) | Επιστρέφει το FileType για το συγκεκριμένο όνομα αρχείου |
| static [FromStream](../../groupdocs.conversion.filetypes/filetype/fromstream)(Stream) | Επιστρέφει το FileType για το παρεχόμενο ρεύμα εγγράφου |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Συγκρίνει το τρέχον αντικείμενο με άλλο. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals#equals)(Enumeration) | Υλοποιεί [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Αναπαράσταση συμβολοσειράς |
| static [GetAll&lt;T&gt;](../../groupdocs.conversion.filetypes/filetype/getall)() | Επιστρέφει όλες τις τιμές της απαρίθμησης. |
| [implicit operator](../../groupdocs.conversion.filetypes/filetype/op_implicit) | Έμμεση μετατροπή σε συμβολοσειρά |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| static readonly [Unknown](../../groupdocs.conversion.filetypes/filetype/unknown) | Άγνωστος τύπος αρχείου |

### Δείτε επίσης

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
