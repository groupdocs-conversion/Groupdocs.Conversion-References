---
title: WordProcessingFileType
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Ορίζει αρχεία επεξεργασίας κειμένου που περιέχουν πληροφορίες χρήστη σε μορφή απλού κειμένου ή εμπλουτισμένου κειμένου. Μια μορφή αρχείου απλού κειμένου περιέχει μη μορφοποιημένο κείμενο και δεν μπορούν να εφαρμοστούν ρυθμίσεις γραμματοσειράς ή σελίδας κ.λπ. Αντίθετα μια μορφή αρχείου εμπλουτισμένου κειμένου επιτρέπει επιλογές μορφοποίησης όπως ορισμό τύπου γραμματοσειράς στυλ έντονα πλάγια υπογράμμιση κ.λπ. περιθώρια σελίδας επικεφαλίδες κουκκίδες και αριθμούς και πολλές άλλες δυνατότητες μορφοποίησης. Περιλαμβάνει τους ακόλουθους τύπους αρχείων Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt . Md./wordprocessingfiletype/md . Log . Μάθετε περισσότερα σχετικά με τις μορφές επεξεργασίας κειμένουεδώhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 1090
url: /el/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Ορίζει αρχεία επεξεργασίας κειμένου που περιέχουν πληροφορίες χρήστη σε μορφή απλού κειμένου ή εμπλουτισμένου κειμένου. Μια μορφή αρχείου απλού κειμένου περιέχει μη μορφοποιημένο κείμενο και δεν μπορούν να εφαρμοστούν ρυθμίσεις γραμματοσειράς ή σελίδας κ.λπ. Αντίθετα, μια μορφή αρχείου εμπλουτισμένου κειμένου επιτρέπει επιλογές μορφοποίησης, όπως ορισμό τύπου γραμματοσειράς, στυλ (έντονα, πλάγια, υπογράμμιση, κ.λπ.), περιθώρια σελίδας, επικεφαλίδες, κουκκίδες και αριθμούς και πολλές άλλες δυνατότητες μορφοποίησης. Περιλαμβάνει τους ακόλουθους τύπους αρχείων: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , Mobi , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`Txt`](./txt) . [`Md`](./md) . Log . Μάθετε περισσότερα σχετικά με τις μορφές επεξεργασίας κειμένου[εδώ](https://wiki.fileformat.com/word-processing) .

```csharp
public sealed class WordProcessingFileType : FileType
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Κατασκευαστής σειριοποίησης |

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
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | Τα αρχεία με επέκταση .doc αντιπροσωπεύουν έγγραφα που δημιουργούνται από το Microsoft Word ή άλλα έγγραφα επεξεργασίας κειμένου σε δυαδική μορφή αρχείου. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | Τα αρχεία DOCM είναι έγγραφα του Microsoft Word 2007 ή νεότερης έκδοσης που δημιουργούνται με δυνατότητα εκτέλεσης μακροεντολών. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | Το Το DOCX είναι μια πολύ γνωστή μορφή για έγγραφα του Microsoft Word. Παρουσιάστηκε από το 2007 με την κυκλοφορία του Microsoft Office 2007, η δομή αυτής της νέας μορφής Εγγράφου άλλαξε από απλό δυαδικό σε συνδυασμό XML και δυαδικών αρχείων. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | Τα αρχεία με επέκταση .DOT είναι αρχεία προτύπων που δημιουργούνται από το Microsoft Word για να έχουν προδιαμορφωμένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOC ή DOCX. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | Ένα αρχείο με επέκταση DOTM αντιπροσωπεύει αρχείο προτύπου που δημιουργήθηκε με Microsoft Word 2007 ή νεότερη έκδοση. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | Τα αρχεία με επέκταση DOTX είναι αρχεία προτύπων που δημιουργήθηκαν από το Microsoft Word για να έχουν προδιαμορφωμένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOCX. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Τα αρχεία κειμένου που δημιουργούνται με διαλέκτους της γλώσσας Markdown αποθηκεύονται με επέκταση αρχείου .MD ή .MARKDOWN. Τα αρχεία MD αποθηκεύονται σε μορφή απλού κειμένου που χρησιμοποιεί τη γλώσσα Markdown, η οποία περιλαμβάνει επίσης σύμβολα ενσωματωμένου κειμένου, καθορίζοντας πώς μπορεί να μορφοποιηθεί ένα κείμενο, όπως εσοχές, μορφοποίηση πίνακα, γραμματοσειρές και κεφαλίδες. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/md) . |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | Τα αρχεία ODT είναι τύπος εγγράφων που δημιουργούνται με εφαρμογές επεξεργασίας κειμένου που βασίζονται σε μορφή αρχείου κειμένου OpenDocument. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | Τα αρχεία με επέκταση OTT αντιπροσωπεύουν έγγραφα προτύπου που δημιουργούνται από εφαρμογές σε συμμόρφωση με την τυπική μορφή OpenDocument του OASIS. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Παρουσιάστηκε και τεκμηριώθηκε από τη Microsoft, το Rich Text Format (RTF) αντιπροσωπεύει μια μέθοδο κωδικοποίησης μορφοποιημένου κειμένου και γραφικών για χρήση σε εφαρμογές. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | Ένα αρχείο με επέκταση .TXT αντιπροσωπεύει ένα έγγραφο κειμένου που περιέχει απλό κείμενο με τη μορφή γραμμών. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/txt) . |

### Δείτε επίσης

* class [FileType](../filetype)
* χώρος ονομάτων [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* συνέλευση [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
