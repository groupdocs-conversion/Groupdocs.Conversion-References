---
title: "CommonConvertOptionsTFileType"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Αφηρημένη γενική κοινή κλάση επιλογών μετατροπής."
type: docs
weight: 1740
url: /el/net/groupdocs.conversion.options.convert/commonconvertoptions-1/
---
## CommonConvertOptions&lt;TFileType&gt; class

Αφηρημένη γενική κοινή κλάση επιλογών μετατροπής.

```csharp
public abstract class CommonConvertOptions<TFileType> : ConvertOptions<TFileType>, 
    IPagedConvertOptions, IPageRangedConvertOptions, IWatermarkedConvertOptions
    where TFileType : FileType
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Ο επιθυμητός τύπος αρχείου στον οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Υλοποιεί [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Υλοποιεί [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Υλοποιεί [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Υλοποιεί [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Υλοποιεί [`Watermark`](../iwatermarkedconvertoptions/watermark) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία επιλογών. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* interface [IPagedConvertOptions](../ipagedconvertoptions)
* interface [IPageRangedConvertOptions](../ipagerangedconvertoptions)
* interface [IWatermarkedConvertOptions](../iwatermarkedconvertoptions)
* class [FileType](../../groupdocs.conversion.filetypes/filetype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
