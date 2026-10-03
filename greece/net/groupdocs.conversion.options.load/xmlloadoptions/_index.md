---
title: "XmlLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων XML."
type: docs
weight: 2960
url: /el/net/groupdocs.conversion.options.load/xmlloadoptions/
---
## XmlLoadOptions class

Επιλογές για τη φόρτωση εγγράφων XML.

```csharp
public sealed class XmlLoadOptions : WebLoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions)() | Αρχικοποιεί νέα παρουσία της κλάσης [`XmlLoadOptions`](../xmlloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BasePath](../../groupdocs.conversion.options.load/webloadoptions/basepath) { get; set; } | Η βασική διαδρομή/URL για το html |
| [ConfigureHeaders](../../groupdocs.conversion.options.load/webloadoptions/configureheaders) { get; set; } | Δράση για τη διαμόρφωση των κεφαλίδων του αιτήματος. Η πρώτη παράμετρος της δράσης είναι το Uri. |
| [CredentialsProvider](../../groupdocs.conversion.options.load/webloadoptions/credentialsprovider) { get; set; } | Πάροχος διαπιστευτηρίων για το Uri. |
| [CustomCssStyle](../../groupdocs.conversion.options.load/webloadoptions/customcssstyle) { get; set; } | Υλοποιεί [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [Encoding](../../groupdocs.conversion.options.load/webloadoptions/encoding) { get; set; } | Λαμβάνει ή ορίζει την κωδικοποίηση που θα χρησιμοποιηθεί κατά τη φόρτωση του διαδικτυακού εγγράφου. Εάν η ιδιότητα είναι null, η κωδικοποίηση θα καθοριστεί από το χαρακτηριστικό συνόλου χαρακτήρων του εγγράφου. |
| [Format](../../groupdocs.conversion.options.load/xmlloadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| [HtmlRenderingMode](../../groupdocs.conversion.options.load/webloadoptions/htmlrenderingmode) { get; set; } | Ελέγχει πώς αποδίδεται το περιεχόμενο HTML. Προεπιλογή: AbsolutePositioning |
| [MarginSettings](../../groupdocs.conversion.options.load/webloadoptions/marginsettings) { get; set; } | Ρυθμίσεις περιθωρίων σελίδας |
| [OrientationSettings](../../groupdocs.conversion.options.load/webloadoptions/orientationsettings) { get; set; } | Ρυθμίσεις προσανατολισμού σελίδας |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/webloadoptions/pagelayoutoptions) { get; set; } | Καθορίζει τις επιλογές διάταξης σελίδας κατά τη φόρτωση διαδικτυακών εγγράφων. |
| [PageNumbering](../../groupdocs.conversion.options.load/webloadoptions/pagenumbering) { get; set; } | Ενεργοποίηση ή απενεργοποίηση της δημιουργίας αρίθμησης σελίδων στο μετατρεπόμενο έγγραφο. Προεπιλογή: false |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/webloadoptions/resourceloadingtimeout) { get; set; } | Χρόνος λήξης για τη φόρτωση εξωτερικών πόρων |
| [SizeSettings](../../groupdocs.conversion.options.load/webloadoptions/sizesettings) { get; set; } | Ρυθμίσεις μεγέθους σελίδας |
| [SkipExternalResources](../../groupdocs.conversion.options.load/webloadoptions/skipexternalresources) { get; set; } | Υλοποιεί [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UseAsDataSource](../../groupdocs.conversion.options.load/xmlloadoptions/useasdatasource) { get; set; } | Χρήση εγγράφου Xml ως πηγή δεδομένων |
| [UsePdf](../../groupdocs.conversion.options.load/webloadoptions/usepdf) { get; set; } | Χρήση pdf για τη μετατροπή. Προεπιλογή: false |
| [WhitelistedResources](../../groupdocs.conversion.options.load/webloadoptions/whitelistedresources) { get; set; } | Υλοποιεί [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |
| [XslFoFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xslfofactory) { get; set; } | Ροή εγγράφου XSL-FO για τη μετατροπή XML χρησιμοποιώντας αρχείο σήμανσης XSL-FO. |
| [XsltFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xsltfactory) { get; set; } | Ροή εγγράφου XSLT για τη μετατροπή XML εκτελώντας μετασχηματισμό XSL σε HTML. |
| [Zoom](../../groupdocs.conversion.options.load/webloadoptions/zoom) { get; set; } | Καθορίζει το επίπεδο ζουμ ως ποσοστό. Το επίπεδο ζουμ εφαρμόζεται στην ετικέτα &lt;body&gt; του εγγράφου πριν από τη μετατροπή, κλιμακώνοντας την οπτική εμφάνιση του εγγράφου. Μια τιμή 100% αντιπροσωπεύει το αρχικό μέγεθος. Η προεπιλεγμένη τιμή είναι 100. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [WebLoadOptions](../webloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
