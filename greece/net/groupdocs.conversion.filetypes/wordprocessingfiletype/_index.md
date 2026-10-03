---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει αρχεία Επεξεργασίας Κειμένου που περιέχουν πληροφορίες χρήστη σε απλό κείμενο ή μορφή εμπλουτισμένου κειμένου. Μια μορφή αρχείου απλού κειμένου περιέχει αμορφοποιημένο κείμενο και δεν μπορούν να εφαρμοστούν ρυθμίσεις γραμματοσειράς ή σελίδας κ.λπ. Αντίθετα, μια μορφή αρχείου εμπλουτισμένου κειμένου επιτρέπει επιλογές μορφοποίησης όπως ορισμός γραμματοσειρών, τύπων, στυλ, έντονη, πλάγια, υπογράμμιση κ.λπ., περιθώρια σελίδας, επικεφαλίδες, κουκίδες και αριθμούς και πολλές άλλες λειτουργίες μορφοποίησης. Περιλαμβάνει τους ακόλουθους τύπους αρχείων Doc./wordprocessingfiletype/doc Docm./wordprocessingfiletype/docm Docx./wordprocessingfiletype/docx Dot./wordprocessingfiletype/dot Dotm./wordprocessingfiletype/dotm Dotx./wordprocessingfiletype/dotx Odt./wordprocessingfiletype/odt Ott./wordprocessingfiletype/ott Rtf./wordprocessingfiletype/rtf Txt./wordprocessingfiletype/txt Md./wordprocessingfiletype/md. Μάθετε περισσότερα για τις μορφές Επεξεργασίας Κειμένου εδώhttps//wiki.fileformat.com/wordprocessing."
type: docs
weight: 1280
url: /el/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Ορίζει αρχεία Επεξεργασίας Κειμένου που περιέχουν πληροφορίες χρήστη σε απλό κείμενο ή μορφή πλούσιου κειμένου. Μια μορφή αρχείου απλού κειμένου περιέχει αμορφοποιημένο κείμενο και δεν μπορεί να εφαρμοστούν ρυθμίσεις γραμματοσειράς ή σελίδας κ.λπ. Αντίθετα, μια μορφή αρχείου πλούσιου κειμένου επιτρέπει επιλογές μορφοποίησης όπως ορισμός τύπων γραμματοσειρών, στυλ (έντονα, πλάγια, υπογραμμισμένα κ.λπ.), περιθώρια σελίδας, επικεφαλίδες, κουκίδες και αριθμοί, και αρκετές άλλες δυνατότητες μορφοποίησης. Περιλαμβάνει τους ακόλουθους τύπους αρχείων: [`Doc`](./doc), [`Docm`](./docm), [`Docx`](./docx), [`Dot`](./dot), [`Dotm`](./dotm), [`Dotx`](./dotx), [`Odt`](./odt), [`Ott`](./ott), [`Rtf`](./rtf), [`Txt`](./txt). [`Md`](./md). Μάθετε περισσότερα για τις μορφές Επεξεργασίας Κειμένου [εδώ](https://wiki.fileformat.com/word-processing).

```csharp
public sealed class WordProcessingFileType : FileType
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Κατασκευαστής σειριοποίησης |

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
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | Τα αρχεία με επέκταση .doc αντιπροσωπεύουν έγγραφα που δημιουργούνται από το Microsoft Word ή άλλα έγγραφα επεξεργασίας κειμένου σε δυαδική μορφή αρχείου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | Τα αρχεία DOCM είναι έγγραφα που δημιουργήθηκαν από το Microsoft Word 2007 ή νεότερο, με τη δυνατότητα εκτέλεσης μακροεντολών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | Το DOCX είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word. Εισήχθη το 2007 με την κυκλοφορία του Microsoft Office 2007, και η δομή αυτής της νέας μορφής εγγράφου άλλαξε από απλό δυαδικό σε συνδυασμό αρχείων XML και δυαδικών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | Τα αρχεία με επέκταση .DOT είναι αρχεία προτύπων που δημιουργήθηκαν από το Microsoft Word για να έχουν προμορφοποιημένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOC ή DOCX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | Ένα αρχείο με επέκταση DOTM αντιπροσωπεύει αρχείο προτύπου που δημιουργήθηκε με το Microsoft Word 2007 ή νεότερο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | Τα αρχεία με επέκταση DOTX είναι αρχεία προτύπων που δημιουργήθηκαν από το Microsoft Word για να έχουν προμορφοποιημένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOCX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/flatopc) | Το Flat OPC Word είναι Office Open XML WordprocessingML αποθηκευμένο σε επίπεδο αρχείο XML αντί για πακέτο ZIP. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Τα αρχεία κειμένου που δημιουργούνται με διαλέκτους της γλώσσας Markdown αποθηκεύονται με την επέκταση .MD ή .MARKDOWN. Τα αρχεία MD αποθηκεύονται σε μορφή απλού κειμένου που χρησιμοποιεί τη γλώσσα Markdown, η οποία περιλαμβάνει επίσης ενσωματωμένα σύμβολα κειμένου, ορίζοντας πώς μπορεί να μορφοποιηθεί ένα κείμενο όπως εσοχές, μορφοποίηση πινάκων, γραμματοσειρές και επικεφαλίδες. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/md). |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | Τα αρχεία ODT είναι τύπος εγγράφων που δημιουργούνται με εφαρμογές επεξεργασίας κειμένου που βασίζονται στη μορφή αρχείου OpenDocument Text. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | Τα αρχεία με επέκταση OTT αντιπροσωπεύουν έγγραφα προτύπων που δημιουργούνται από εφαρμογές σε συμμόρφωση με το πρότυπο OpenDocument του OASIS. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Εισήχθη και τεκμηριώθηκε από τη Microsoft, η μορφή Rich Text Format (RTF) αντιπροσωπεύει μια μέθοδο κωδικοποίησης μορφοποιημένου κειμένου και γραφικών για χρήση σε εφαρμογές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | Ένα αρχείο με επέκταση .TXT αντιπροσωπεύει ένα έγγραφο κειμένου που περιέχει απλό κείμενο σε μορφή γραμμών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/txt). |

### Δείτε επίσης

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
