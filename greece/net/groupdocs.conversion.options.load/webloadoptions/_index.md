---
title: "WebLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων web."
type: docs
weight: 2920
url: /el/net/groupdocs.conversion.options.load/webloadoptions/
---
## WebLoadOptions class

Επιλογές για τη φόρτωση εγγράφων web.

```csharp
public class WebLoadOptions : LoadOptions, ICustomCssStyleOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageOrientationOptions, IPageSizeOptions, 
    IResourceLoadingOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [WebLoadOptions](webloadoptions)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [`WebLoadOptions`](../webloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BasePath](../../groupdocs.conversion.options.load/webloadoptions/basepath) { get; set; } | Η βασική διαδρομή/URL για το html |
| [ConfigureHeaders](../../groupdocs.conversion.options.load/webloadoptions/configureheaders) { get; set; } | Δράση για τη διαμόρφωση των κεφαλίδων του αιτήματος. Η πρώτη παράμετρος της δράσης είναι το Uri. |
| [CredentialsProvider](../../groupdocs.conversion.options.load/webloadoptions/credentialsprovider) { get; set; } | Πάροχος διαπιστευτηρίων για το Uri. |
| [CustomCssStyle](../../groupdocs.conversion.options.load/webloadoptions/customcssstyle) { get; set; } | Υλοποιεί [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [Encoding](../../groupdocs.conversion.options.load/webloadoptions/encoding) { get; set; } | Λαμβάνει ή ορίζει την κωδικοποίηση που θα χρησιμοποιηθεί κατά τη φόρτωση του διαδικτυακού εγγράφου. Εάν η ιδιότητα είναι null, η κωδικοποίηση θα καθοριστεί από το χαρακτηριστικό συνόλου χαρακτήρων του εγγράφου. |
| [Format](../../groupdocs.conversion.options.load/webloadoptions/format) { get; set; } | Τύπος αρχείου εισαγόμενου εγγράφου. Είναι `null` μέχρι να οριστεί μια μορφή, έτσι ελέγξτε το για `null` αντί να το συγκρίνετε με [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), το οποίο ποτέ δεν ισούται. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| [HtmlRenderingMode](../../groupdocs.conversion.options.load/webloadoptions/htmlrenderingmode) { get; set; } | Ελέγχει πώς αποδίδεται το περιεχόμενο HTML. Προεπιλογή: AbsolutePositioning |
| [MarginSettings](../../groupdocs.conversion.options.load/webloadoptions/marginsettings) { get; set; } | Ρυθμίσεις περιθωρίων σελίδας |
| [OrientationSettings](../../groupdocs.conversion.options.load/webloadoptions/orientationsettings) { get; set; } | Ρυθμίσεις προσανατολισμού σελίδας |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/webloadoptions/pagelayoutoptions) { get; set; } | Καθορίζει τις επιλογές διάταξης σελίδας κατά τη φόρτωση διαδικτυακών εγγράφων. |
| [PageNumbering](../../groupdocs.conversion.options.load/webloadoptions/pagenumbering) { get; set; } | Ενεργοποίηση ή απενεργοποίηση της δημιουργίας αρίθμησης σελίδων στο μετατρεπόμενο έγγραφο. Προεπιλογή: false |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/webloadoptions/resourceloadingtimeout) { get; set; } | Χρόνος λήξης για τη φόρτωση εξωτερικών πόρων |
| [SizeSettings](../../groupdocs.conversion.options.load/webloadoptions/sizesettings) { get; set; } | Ρυθμίσεις μεγέθους σελίδας |
| [SkipExternalResources](../../groupdocs.conversion.options.load/webloadoptions/skipexternalresources) { get; set; } | Υλοποιεί [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UsePdf](../../groupdocs.conversion.options.load/webloadoptions/usepdf) { get; set; } | Χρήση pdf για τη μετατροπή. Προεπιλογή: false |
| [WhitelistedResources](../../groupdocs.conversion.options.load/webloadoptions/whitelistedresources) { get; set; } | Υλοποιεί [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |
| [Zoom](../../groupdocs.conversion.options.load/webloadoptions/zoom) { get; set; } | Καθορίζει το επίπεδο ζουμ ως ποσοστό. Το επίπεδο ζουμ εφαρμόζεται στην ετικέτα &lt;body&gt; του εγγράφου πριν από τη μετατροπή, κλιμακώνοντας την οπτική εμφάνιση του εγγράφου. Μια τιμή 100% αντιπροσωπεύει το αρχικό μέγεθος. Η προεπιλεγμένη τιμή είναι 100. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [LoadOptions](../loadoptions)
* interface [ICustomCssStyleOptions](../icustomcssstyleoptions)
* interface [IPageLayoutOptions](../ipagelayoutoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
