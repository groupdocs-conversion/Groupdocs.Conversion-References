---
title: WordProcessingConvertOptions
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Επιλογές για μετατροπή σε τύπο αρχείου WordProcessing.
type: docs
weight: 2000
url: /el/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

Επιλογές για μετατροπή σε τύπο αρχείου WordProcessing.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IPageMarginConvertOptions, IPageOrientationConvertOptions, IPageSizeConvertOptions, 
    IPdfRecognitionModeOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | Αρχικοποιεί νέα παρουσία του[`WordProcessingConvertOptions`](../wordprocessingconvertoptions) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | Επιθυμητό DPI σελίδας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι: 96 dpi. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Ο επιθυμητός τύπος αρχείου στο οποίο θα πρέπει να μετατραπεί το έγγραφο εισόδου. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Ο επιθυμητός τύπος αρχείου στο οποίο θα πρέπει να μετατραπεί το έγγραφο εισόδου. |
| [Height](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/height) { get; set; } | Επιθυμητό ύψος σελίδας μετά τη μετατροπή. |
| [MarginBottom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginbottom) { get; set; } | Επιθυμητό κάτω περιθώριο σελίδας σε pixel μετά τη μετατροπή. |
| [MarginLeft](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginleft) { get; set; } | Επιθυμητό αριστερό περιθώριο σελίδας σε pixel μετά τη μετατροπή. |
| [MarginRight](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginright) { get; set; } | Επιθυμητό δεξί περιθώριο σελίδας σε pixel μετά τη μετατροπή. |
| [MarginTop](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/margintop) { get; set; } | Επιθυμητό επάνω περιθώριο σελίδας σε pixel μετά τη μετατροπή. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Ο αριθμός σελίδας από τον οποίο θα ξεκινήσει η μετατροπή. |
| [PageOrientation](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pageorientation) { get; set; } | Επιθυμητός προσανατολισμός σελίδας μετά τη μετατροπή |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Η λίστα των ευρετηρίων σελίδων προς μετατροπή. Θα πρέπει να καθοριστεί για τη μετατροπή συγκεκριμένων σελίδων. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Αριθμός σελίδων για μετατροπή ξεκινώντας από`Αριθμός σελίδας` . |
| [PageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pagesize) { get; set; } | Επιθυμητό μέγεθος σελίδας μετά τη μετατροπή |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | Ορίστε αυτήν την ιδιότητα εάν θέλετε να προστατεύσετε το έγγραφο που έχει μετατραπεί με κωδικό πρόσβασης. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | Λειτουργία αναγνώρισης κατά τη μετατροπή από pdf |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | Επιλογές μετατροπής ειδικών RTF |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Ειδικές επιλογές υδατογραφήματος |
| [Width](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/width) { get; set; } | Επιθυμητό πλάτος σελίδας μετά τη μετατροπή. |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | Καθορίζει το επίπεδο ζουμ σε ποσοστό. Η προεπιλογή είναι 100. Το προεπιλεγμένο ζουμ υποστηρίζεται μέχρι το Microsoft Word 2010. Ξεκινώντας από το Microsoft Word 2013, το προεπιλεγμένο ζουμ δεν είναι πλέον ρυθμισμένο σε έγγραφο, αντίθετα φαίνεται να χρησιμοποιεί τον παράγοντα ζουμ του τελευταίου εγγράφου που ανοίχτηκε. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία επιλογών. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Εξυπηρετεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* χώρος ονομάτων [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* συνέλευση [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
