---
title: "RasterImageLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων εικόνας."
type: docs
weight: 2800
url: /el/net/groupdocs.conversion.options.load/rasterimageloadoptions/
---
## RasterImageLoadOptions class

Επιλογές για τη φόρτωση εγγράφων εικόνας.

```csharp
public sealed class RasterImageLoadOptions : BaseImageLoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [RasterImageLoadOptions](rasterimageloadoptions)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [`RasterImageLoadOptions`](../rasterimageloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CropArea](../../groupdocs.conversion.options.load/rasterimageloadoptions/croparea) { get; set; } | Κόψτε την περιοχή της εικόνας πριν από τη μετατροπή. |
| [DefaultFont](../../groupdocs.conversion.options.load/baseimageloadoptions/defaultfont) { get; set; } | Προεπιλεγμένη γραμματοσειρά για τύπους εγγράφων Psd, Emf, Wmf. Η παρακάτω γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά. |
| [Format](../../groupdocs.conversion.options.load/rasterimageloadoptions/format) { get; set; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/baseimageloadoptions/resetfontfolders) { get; set; } | Επαναφορά φακέλων γραμματοσειρών πριν τη φόρτωση του εγγράφου |
| [VectorizationOptions](../../groupdocs.conversion.options.load/rasterimageloadoptions/vectorizationoptions) { get; set; } | Ορίζει επιλογές διανυσματισμού. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |
| [SetHeicConnector](../../groupdocs.conversion.options.load/rasterimageloadoptions/setheicconnector)(IHeicConnector) | Ορίστε το διασυνδετικό εικόνας Heic. |
| [SetOcrConnector](../../groupdocs.conversion.options.load/rasterimageloadoptions/setocrconnector)(IOcrConnector) | Ορίστε το διασυνδετικό OCR εικόνας. |

### Δείτε επίσης

* class [BaseImageLoadOptions](../baseimageloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
