---
title: "EBookConvertOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για μετατροπή σε τύπο αρχείου Ηλεκτρονικό βιβλίο."
type: docs
weight: 1790
url: /el/net/groupdocs.conversion.options.convert/ebookconvertoptions/
---
## EBookConvertOptions class

Επιλογές για μετατροπή σε τύπο αρχείου Ηλεκτρονικό βιβλίο.

```csharp
public class EBookConvertOptions : CommonConvertOptions<EBookFileType>, IPageOrientationOptions, 
    IPageSizeOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [EBookConvertOptions](ebookconvertoptions)() | Αρχικοποιεί νέα παρουσία της κλάσης [`EBookConvertOptions`](../ebookconvertoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/ebookconvertoptions/fallbackpagesize) { get; set; } | Εφεδρικό μέγεθος σελίδας |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Ο επιθυμητός τύπος αρχείου στον οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Υλοποιεί [`Format`](../iconvertoptions/format) |
| [OrientationSettings](../../groupdocs.conversion.options.convert/ebookconvertoptions/orientationsettings) { get; set; } | Ρυθμίσεις προσανατολισμού σελίδας |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Υλοποιεί [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Υλοποιεί [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Υλοποιεί [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [SizeSettings](../../groupdocs.conversion.options.convert/ebookconvertoptions/sizesettings) { get; set; } | Ρυθμίσεις μεγέθους σελίδας |
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
* class [EBookFileType](../../groupdocs.conversion.filetypes/ebookfiletype)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
