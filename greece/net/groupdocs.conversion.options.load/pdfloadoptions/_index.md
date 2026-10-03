---
title: "PdfLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων Pdf."
type: docs
weight: 2740
url: /el/net/groupdocs.conversion.options.load/pdfloadoptions/
---
## PdfLoadOptions class

Επιλογές για τη φόρτωση εγγράφων Pdf.

```csharp
public sealed class PdfLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageNumberingLoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PdfLoadOptions](pdfloadoptions)() | Αρχικοποιεί νέα παρουσία της κλάσης [`PdfLoadOptions`](../pdfloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearbuiltindocumentproperties) { get; set; } | Αφαιρεί ενσωματωμένες ιδιότητες μεταδεδομένων από το έγγραφο. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearcustomdocumentproperties) { get; set; } | Αφαιρεί προσαρμοσμένες ιδιότητες μεταδεδομένων από το έγγραφο. |
| [ConvertOwned](../../groupdocs.conversion.options.load/pdfloadoptions/convertowned) { get; set; } | Υλοποιεί [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Η προεπιλογή είναι false |
| [ConvertOwner](../../groupdocs.conversion.options.load/pdfloadoptions/convertowner) { get; set; } | Υλοποιεί [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Η προεπιλογή είναι true |
| [DefaultFont](../../groupdocs.conversion.options.load/pdfloadoptions/defaultfont) { get; set; } | Προεπιλεγμένη γραμματοσειρά για έγγραφο Pdf. Η παρακάτω γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά. |
| [Depth](../../groupdocs.conversion.options.load/pdfloadoptions/depth) { get; set; } | Υλοποιεί [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Προεπιλογή: 1 |
| [FlattenAllFields](../../groupdocs.conversion.options.load/pdfloadoptions/flattenallfields) { get; set; } | Ισοπεδώνει όλα τα πεδία της φόρμας PDF. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/pdfloadoptions/fontsubstitutes) { get; set; } | Αντικαθιστά συγκεκριμένες γραμματοσειρές κατά τη μετατροπή εγγράφου Pdf. |
| [FontTransformations](../../groupdocs.conversion.options.load/pdfloadoptions/fonttransformations) { get; set; } | Μετασχηματίζει τις υπάρχουσες γραμματοσειρές μετά τη φόρτωση του εγγράφου και την ολοκλήρωση της αντικατάστασης γραμματοσειρών. Οι μετασχηματισμοί γραμματοσειρών μπορούν να τροποποιήσουν οποιεσδήποτε γραμματοσειρές στο έγγραφο, συμπεριλαμβανομένων των γραμματοσειρών που φορτώθηκαν επιτυχώς. |
| [Format](../../groupdocs.conversion.options.load/pdfloadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. Είναι `null` μέχρι να οριστεί μια μορφή, έτσι ελέγξτε το για `null` αντί να το συγκρίνετε με [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), το οποίο ποτέ δεν ισούται. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| [HidePdfAnnotations](../../groupdocs.conversion.options.load/pdfloadoptions/hidepdfannotations) { get; set; } | Απόκρυψη σχολίων σε έγγραφα Pdf. |
| [PageNumbering](../../groupdocs.conversion.options.load/pdfloadoptions/pagenumbering) { get; set; } | Ενεργοποίηση ή απενεργοποίηση της δημιουργίας αρίθμησης σελίδων στο μετατρεπόμενο έγγραφο. Προεπιλογή: false |
| [Password](../../groupdocs.conversion.options.load/pdfloadoptions/password) { get; set; } | Ορίστε κωδικό πρόσβασης για την αφαίρεση προστασίας του προστατευμένου εγγράφου. |
| [RemoveEmbeddedFiles](../../groupdocs.conversion.options.load/pdfloadoptions/removeembeddedfiles) { get; set; } | Αφαίρεση ενσωματωμένων αρχείων. |
| [RemoveJavascript](../../groupdocs.conversion.options.load/pdfloadoptions/removejavascript) { get; set; } | Αφαίρεση javascript. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/pdfloadoptions/resetfontfolders) { get; set; } | Επαναφορά φακέλων γραμματοσειρών πριν τη φόρτωση του εγγράφου |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
