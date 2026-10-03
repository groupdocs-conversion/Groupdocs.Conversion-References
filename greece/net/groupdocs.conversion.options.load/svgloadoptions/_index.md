---
title: "SvgLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων Svg."
type: docs
weight: 2830
url: /el/net/groupdocs.conversion.options.load/svgloadoptions/
---
## SvgLoadOptions class

Επιλογές για τη φόρτωση εγγράφων Svg.

```csharp
public class SvgLoadOptions : LoadOptions, IResourceLoadingOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SvgLoadOptions](svgloadoptions)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SvgLoadOptions`](../svgloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CropToContentBounds](../../groupdocs.conversion.options.load/svgloadoptions/croptocontentbounds) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα περικοπεί το πλαίσιο οριοθέτησης του SVG στα όρια του περιεχομένου πριν από τη μετατροπή. Η προεπιλογή είναι false. |
| [Format](../../groupdocs.conversion.options.load/svgloadoptions/format) { get; set; } | Τύπος αρχείου εισαγόμενου εγγράφου. Είναι `null` μέχρι να οριστεί μια μορφή, έτσι ελέγξτε το για `null` αντί να το συγκρίνετε με [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), το οποίο ποτέ δεν ισούται. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| [MinimumHeight](../../groupdocs.conversion.options.load/svgloadoptions/minimumheight) { get; set; } | Ορίζει το ελάχιστο ύψος για τη μετατροπή του εγγράφου SVG. Χρησιμοποιείται κατά τη μετατροπή σε μορφές raster. Η προεπιλογή είναι 600. |
| [MinimumWidth](../../groupdocs.conversion.options.load/svgloadoptions/minimumwidth) { get; set; } | Ορίζει το ελάχιστο πλάτος για τη μετατροπή του εγγράφου SVG. Χρησιμοποιείται κατά τη μετατροπή σε μορφές raster. Η προεπιλογή είναι 800. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/svgloadoptions/skipexternalresources) { get; set; } | Υλοποιεί [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/svgloadoptions/whitelistedresources) { get; set; } | Εξωτερικοί πόροι που θα φορτώνονται πάντα. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [LoadOptions](../loadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
