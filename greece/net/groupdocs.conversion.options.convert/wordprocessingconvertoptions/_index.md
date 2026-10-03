---
title: "WordProcessingConvertOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές μετατροπής σε τύπο αρχείου Επεξεργασίας Κειμένου."
type: docs
weight: 2340
url: /el/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

Επιλογές μετατροπής σε τύπο αρχείου Επεξεργασίας Κειμένου.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IDpiConvertOptions, IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, 
    IPasswordConvertOptions, IPdfRecognitionModeOptions, IZoomConvertOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | Αρχικοποιεί νέα παρουσία της κλάσης [`WordProcessingConvertOptions`](../wordprocessingconvertoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | Επιθυμητό DPI σελίδας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι: 96 dpi. |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallbackpagesize) { get; set; } | Εφεδρικό μέγεθος σελίδας |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Ο επιθυμητός τύπος αρχείου στον οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Υλοποιεί [`Format`](../iconvertoptions/format) |
| [MarginSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginsettings) { get; set; } | Ρυθμίσεις περιθωρίων σελίδας |
| [MarkdownOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdownoptions) { get; set; } | Υλοποιεί [`MarkdownOptions`](./markdownoptions) |
| [OrientationSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/orientationsettings) { get; set; } | Ρυθμίσεις προσανατολισμού σελίδας |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Υλοποιεί [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Υλοποιεί [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Υλοποιεί [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | Ορίστε αυτήν την ιδιότητα εάν θέλετε να προστατεύσετε το μετατρεπόμενο έγγραφο με κωδικό πρόσβασης. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | Υλοποιεί [`PdfRecognitionMode`](../ipdfrecognitionmodeoptions/pdfrecognitionmode) |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | Ειδικές επιλογές μετατροπής RTF |
| [SizeSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/sizesettings) { get; set; } | Ρυθμίσεις μεγέθους σελίδας |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Υλοποιεί [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | Καθορίζει το επίπεδο ζουμ σε ποσοστό. Η προεπιλογή είναι 100. Το προεπιλεγμένο ζουμ υποστηρίζεται έως το Microsoft Word 2010. Από το Microsoft Word 2013 το προεπιλεγμένο ζουμ δεν ορίζεται πλέον στο έγγραφο, αλλά φαίνεται να χρησιμοποιεί τον παράγοντα ζουμ του τελευταίου ανοιγμένου εγγράφου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία επιλογών. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IDpiConvertOptions](../idpiconvertoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
