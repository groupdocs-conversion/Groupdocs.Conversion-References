---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων Presentation."
type: docs
weight: 2770
url: /el/net/groupdocs.conversion.options.load/presentationloadoptions/
---
## PresentationLoadOptions class

Επιλογές για τη φόρτωση εγγράφων Presentation.

```csharp
public class PresentationLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IMetadataLoadOptions, IResourceLoadingOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PresentationLoadOptions](presentationloadoptions)() | Αρχικοποιεί νέα παρουσία της κλάσης [`PresentationLoadOptions`](../presentationloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearbuiltindocumentproperties) { get; set; } | Αφαιρεί ενσωματωμένες ιδιότητες μεταδεδομένων από το έγγραφο. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearcustomdocumentproperties) { get; set; } | Αφαιρεί προσαρμοσμένες ιδιότητες μεταδεδομένων από το έγγραφο. |
| [CommentsPosition](../../groupdocs.conversion.options.load/presentationloadoptions/commentsposition) { get; set; } | Αναπαριστά τον τρόπο με τον οποίο εκτυπώνονται τα σχόλια με τη διαφάνεια. Η προεπιλογή είναι None. |
| [ConvertOwned](../../groupdocs.conversion.options.load/presentationloadoptions/convertowned) { get; set; } | Υλοποιεί [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Η προεπιλογή είναι false |
| [ConvertOwner](../../groupdocs.conversion.options.load/presentationloadoptions/convertowner) { get; set; } | Υλοποιεί [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Η προεπιλογή είναι true |
| [DefaultFont](../../groupdocs.conversion.options.load/presentationloadoptions/defaultfont) { get; set; } | Προεπιλεγμένη γραμματοσειρά για την απόδοση της παρουσίασης. Η παρακάτω γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει η γραμματοσειρά της παρουσίασης. |
| [Depth](../../groupdocs.conversion.options.load/presentationloadoptions/depth) { get; set; } | Υλοποιεί [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Προεπιλογή: 1 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/presentationloadoptions/fontsubstitutes) { get; set; } | Αντικαταστήστε συγκεκριμένες γραμματοσειρές κατά τη μετατροπή του εγγράφου Presentation. |
| [Format](../../groupdocs.conversion.options.load/presentationloadoptions/format) { get; set; } | Τύπος αρχείου εισαγόμενου εγγράφου. Είναι `null` μέχρι να οριστεί μια μορφή, έτσι ελέγξτε το για `null` αντί να το συγκρίνετε με [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), το οποίο ποτέ δεν ισούται. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| [NotesPosition](../../groupdocs.conversion.options.load/presentationloadoptions/notesposition) { get; set; } | Αναπαριστά τον τρόπο με τον οποίο εκτυπώνονται οι σημειώσεις με τη διαφάνεια. Η προεπιλογή είναι None. |
| [Password](../../groupdocs.conversion.options.load/presentationloadoptions/password) { get; set; } | Ορίστε κωδικό πρόσβασης για την αφαίρεση προστασίας του προστατευμένου εγγράφου. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/presentationloadoptions/preservedocumentstructure) { get; set; } | Καθορίζει αν η δομή του εγγράφου πρέπει να διατηρηθεί κατά τη μετατροπή σε PDF (η προεπιλογή είναι false). |
| [ShowHiddenSlides](../../groupdocs.conversion.options.load/presentationloadoptions/showhiddenslides) { get; set; } | Εμφάνιση κρυφών διαφανειών. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/presentationloadoptions/skipexternalresources) { get; set; } | Υλοποιεί [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/presentationloadoptions/whitelistedresources) { get; set; } | Υλοποιεί [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |
| [SetVideoConnector](../../groupdocs.conversion.options.load/presentationloadoptions/setvideoconnector)(IPresentationVideoConnector) | Ορίστε το σύνδεσμο του εγγράφου βίντεο |

### Δείτε επίσης

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
