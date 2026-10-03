---
title: "PdfConvertOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για μετατροπή σε τύπο αρχείου Pdf."
type: docs
weight: 2060
url: /el/net/groupdocs.conversion.options.convert/pdfconvertoptions/
---
## PdfConvertOptions class

Επιλογές για μετατροπή σε τύπο αρχείου Pdf.

```csharp
public class PdfConvertOptions : CommonConvertOptions<PdfFileType>, IDpiConvertOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IPasswordConvertOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PdfConvertOptions](pdfconvertoptions)() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PdfConvertOptions`](../pdfconvertoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/pdfconvertoptions/dpi) { get; set; } | Επιθυμητό DPI σελίδας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι: 96 dpi. |
| [EmbedFullFonts](../../groupdocs.conversion.options.convert/pdfconvertoptions/embedfullfonts) { get; set; } | Όταν οριστεί σε true, το πλήρες αρχείο γραμματοσειράς ενσωματώνεται στο PDF αντί για ένα υποσύνολο. Αυτό αυξάνει το μέγεθος του αρχείου εξόδου αλλά εξασφαλίζει καλύτερη συμβατότητα κατά την επεξεργασία του παραγόμενου PDF. Ισχύει μόνο κατά τη μετατροπή από έγγραφα WordProcessing. |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/pdfconvertoptions/fallbackpagesize) { get; set; } | Εφεδρικό μέγεθος σελίδας |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Ο επιθυμητός τύπος αρχείου στον οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Υλοποιεί [`Format`](../iconvertoptions/format) |
| [MarginSettings](../../groupdocs.conversion.options.convert/pdfconvertoptions/marginsettings) { get; set; } | Ρυθμίσεις περιθωρίων σελίδας |
| [OrientationSettings](../../groupdocs.conversion.options.convert/pdfconvertoptions/orientationsettings) { get; set; } | Ρυθμίσεις προσανατολισμού σελίδας |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Υλοποιεί [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Υλοποιεί [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Υλοποιεί [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/pdfconvertoptions/password) { get; set; } | Ορίστε αυτήν την ιδιότητα εάν θέλετε να προστατεύσετε το μετατρεπόμενο έγγραφο με κωδικό πρόσβασης. |
| [PdfOptions](../../groupdocs.conversion.options.convert/pdfconvertoptions/pdfoptions) { get; set; } | Ειδικές επιλογές μετατροπής PDF |
| [ResizeMode](../../groupdocs.conversion.options.convert/pdfconvertoptions/resizemode) { get; set; } | Καθορίζει πώς πρέπει να κλιμακώται το περιεχόμενο όταν αλλάζει το μέγεθος της σελίδας. Η προεπιλογή είναι AlignTopLeft (χωρίς κλιμάκωση). |
| [Rotate](../../groupdocs.conversion.options.convert/pdfconvertoptions/rotate) { get; set; } | Περιστροφή σελίδας |
| [SizeSettings](../../groupdocs.conversion.options.convert/pdfconvertoptions/sizesettings) { get; set; } | Ρυθμίσεις μεγέθους σελίδας |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Υλοποιεί [`Watermark`](../iwatermarkedconvertoptions/watermark) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία επιλογών. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PdfFileType](../../groupdocs.conversion.filetypes/pdffiletype)
* interface [IDpiConvertOptions](../idpiconvertoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
