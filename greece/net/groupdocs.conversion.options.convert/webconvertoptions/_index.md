---
title: "WebConvertOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές μετατροπής σε τύπο αρχείου Web."
type: docs
weight: 2320
url: /el/net/groupdocs.conversion.options.convert/webconvertoptions/
---
## WebConvertOptions class

Επιλογές μετατροπής σε τύπο αρχείου Web.

```csharp
public class WebConvertOptions : CommonConvertOptions<WebFileType>, IUsePdfConvertOptions, 
    IZoomConvertOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [WebConvertOptions](webconvertoptions)() | Αρχικοποιεί νέο στιγμιότυπο της κλάσης [`WebConvertOptions`](../webconvertoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [EmbedFontResources](../../groupdocs.conversion.options.convert/webconvertoptions/embedfontresources) { get; set; } | Καθορίζει εάν θα ενσωματωθούν οι πόροι γραμματοσειρών μέσα στο κύριο HTML. Η προεπιλογή είναι ψευδής. Σημείωση: Εάν το FixedLayout οριστεί σε αληθές, οι πόροι γραμματοσειρών θα ενσωματώνονται πάντα. |
| [FixedLayout](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayout) { get; set; } | Εάν `true`, θα χρησιμοποιηθεί σταθερή διάταξη, π.χ. απόλυτα τοποθετημένα στοιχεία html. Προεπιλογή: true |
| [FixedLayoutShowBorders](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayoutshowborders) { get; set; } | Εμφάνιση περιγραμμάτων σελίδας κατά τη μετατροπή σε σταθερή διάταξη. Η προεπιλογή είναι αληθής. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Ο επιθυμητός τύπος αρχείου στον οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Υλοποιεί [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Υλοποιεί [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Υλοποιεί [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Υλοποιεί [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [SlideShow](../../groupdocs.conversion.options.convert/webconvertoptions/slideshow) { get; set; } | Ισχύει μόνο για τη μετατροπή μιας παρουσίασης σε [`Html`](../../groupdocs.conversion.filetypes/webfiletype/html) ή [`Htm`](../../groupdocs.conversion.filetypes/webfiletype/htm) και αγνοείται για κάθε άλλη μετατροπή. Καθορίζει εάν η παρουσίαση θα γίνει διαδραστική παρουσίαση HTML με μεταβάσεις διαφανειών και κινήσεις σχημάτων, αντί για την προεπιλεγμένη στατική σελίδα HTML. Η προεπιλογή είναι ψευδής. |
| [UsePdf](../../groupdocs.conversion.options.convert/webconvertoptions/usepdf) { get; set; } | Εάν `true`, η είσοδος πρώτα μετατρέπεται σε PDF και μετά στο επιθυμητό μορφότυπο. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Υλοποιεί [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/webconvertoptions/zoom) { get; set; } | Καθορίζει το επίπεδο ζουμ σε ποσοστό. Η προεπιλογή είναι 100. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία επιλογών. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WebFileType](../../groupdocs.conversion.filetypes/webfiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
