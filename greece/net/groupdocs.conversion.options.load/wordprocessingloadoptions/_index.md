---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων WordProcessing."
type: docs
weight: 2950
url: /el/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

Επιλογές για τη φόρτωση εγγράφων WordProcessing.

```csharp
public class WordProcessingLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [`WordProcessingLoadOptions`](../wordprocessingloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AutoDetectRtlDirection](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection) { get; set; } | Όταν είναι true (προεπιλογή), οι παράγραφοι και τα runs των οποίων το κείμενο είναι κυρίως από δεξιά προς τα αριστερά θα έχουν τα bidi flags τους διορθωμένα πριν από τη μετατροπή. Αυτό ταιριάζει με την ευρετική που εφαρμόζουν τα Microsoft Word και LibreOffice και διορθώνει την απόδοση των εγγράφων Αραβικών/Εβραϊκών που παράγονται από δημιουργούς (ιδιαίτερα Google Docs) που εκδίδουν OOXML χωρίς &lt;w:bidi/&gt; και με &lt;w:rtl w:val=\"0\"/&gt; σε runs που περιέχουν μόνο RTL script. Ορίστε σε false για να διατηρήσετε την αυστηρή ερμηνεία του OOXML του πρωτοτύπου markup. |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | Επιλογές σελιδοδεικτών |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearbuiltindocumentproperties) { get; set; } | Αφαιρεί ενσωματωμένες ιδιότητες μεταδεδομένων από το έγγραφο. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearcustomdocumentproperties) { get; set; } | Αφαιρεί προσαρμοσμένες ιδιότητες μεταδεδομένων από το έγγραφο. |
| [CommentDisplayMode](../../groupdocs.conversion.options.load/wordprocessingloadoptions/commentdisplaymode) { get; set; } | Καθορίζει πώς πρέπει να εμφανίζονται τα σχόλια στο έγγραφο εξόδου. Η προεπιλογή είναι ShowInBalloons. |
| [ConvertOwned](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowned) { get; set; } | Υλοποιεί [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Η προεπιλογή είναι false |
| [ConvertOwner](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowner) { get; set; } | Υλοποιεί [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Η προεπιλογή είναι true |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | Ορίζει τη προεπιλεγμένη γραμματοσειρά για ένα έγγραφο WordProcessing. |
| [Depth](../../groupdocs.conversion.options.load/wordprocessingloadoptions/depth) { get; set; } | Υλοποιεί [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Προεπιλογή: 1 |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | Εάν το EmbedTrueTypeFonts είναι true, το GroupDocs.Conversion ενσωματώνει γραμματοσειρές TrueType στο έγγραφο εξόδου. Προεπιλογή: true |
| [FontConfigSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled) { get; set; } | Αντικαθιστά αυτόματα τις ελλιπείς γραμματοσειρές βάσει του FontConfig στο σύστημα. Προεπιλογή: false. |
| [FontInfoSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled) { get; set; } | Αντικαθιστά αυτόματα τις ελλιπείς γραμματοσειρές βάσει του FontInfo στο έγγραφο. Προεπιλογή: false. |
| [FontNameSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled) { get; set; } | Αντικαθιστά αυτόματα τις ελλιπείς γραμματοσειρές βάσει του ονόματος γραμματοσειράς. Προεπιλογή: false. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | Αντικαθιστά συγκεκριμένες γραμματοσειρές κατά τη μετατροπή ενός εγγράφου WordsProcessing. |
| [FontTransformations](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations) { get; set; } | Μετασχηματίζει τις υπάρχουσες γραμματοσειρές μετά τη φόρτωση του εγγράφου και την ολοκλήρωση της αντικατάστασης γραμματοσειρών. Οι μετασχηματισμοί γραμματοσειρών μπορούν να τροποποιήσουν οποιεσδήποτε γραμματοσειρές στο έγγραφο, συμπεριλαμβανομένων των γραμματοσειρών που φορτώθηκαν επιτυχώς. |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | Τύπος αρχείου εισαγόμενου εγγράφου. Είναι `null` μέχρι να οριστεί μια μορφή, έτσι ελέγξτε το για `null` αντί να το συγκρίνετε με [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), το οποίο ποτέ δεν ισούται. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | Απόκρυψη σήμανσης και παρακολούθηση αλλαγών για έγγραφα Word. |
| [HyphenationOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenationoptions) { get; set; } | Ορίστε επιλογές συλλαβισμού για έγγραφα WordProcessing. |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | Διατηρεί την αρχική τιμή του πεδίου ημερομηνίας. Προεπιλογή: false |
| [MarginSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/marginsettings) { get; set; } | Ρυθμίσεις περιθωρίων σελίδας |
| [PageNumbering](../../groupdocs.conversion.options.load/wordprocessingloadoptions/pagenumbering) { get; set; } | Ενεργοποίηση ή απενεργοποίηση της δημιουργίας αρίθμησης σελίδων στο μετατρεπόμενο έγγραφο. Προεπιλογή: false |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | Ορίστε κωδικό πρόσβασης για την αφαίρεση προστασίας του προστατευμένου εγγράφου. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preservedocumentstructure) { get; set; } | Καθορίζει αν η δομή του εγγράφου πρέπει να διατηρηθεί κατά τη μετατροπή σε PDF (η προεπιλογή είναι false). |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | Καθορίζει αν θα διατηρηθούν τα πεδία φόρμας του Microsoft Word ως πεδία φόρμας σε PDF ή θα μετατραπούν σε κείμενο. Η προεπιλογή είναι false. |
| [ShowFullCommenterName](../../groupdocs.conversion.options.load/wordprocessingloadoptions/showfullcommentername) { get; set; } | Εμφάνιση πλήρους ονόματος σχολιαστή στα σχόλια. Η προεπιλογή είναι false. |
| [SizeSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/sizesettings) { get; set; } | Ρυθμίσεις μεγέθους σελίδας |
| [SkipExternalResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/skipexternalresources) { get; set; } | Υλοποιεί [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | Ενημέρωση πεδίων μετά τη φόρτωση. Προεπιλογή: false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | Ενημέρωση διάταξης σελίδας μετά τη φόρτωση. Προεπιλογή: false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | Καθορίζει αν θα χρησιμοποιηθεί ένας μορφοποιητής κειμένου για καλύτερη εμφάνιση του kerning. Η προεπιλογή είναι false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/whitelistedresources) { get; set; } | Υλοποιεί [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Παρατηρήσεις

**Font Processing Pipeline:**

**Phase 1 - Font Substitution (during document loading):**

• Διαχειρίζεται ελλιπείς/μη διαθέσιμες γραμματοσειρές χρησιμοποιώντας FontSubstitutes, DefaultFont και αντικατάσταση συστήματος

• Σειρά επεξεργασίας: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

**Phase 2 - Font Replacement (after document loading):**

• Τροποποιεί τυχόν υπάρχουσες γραμματοσειρές στο φορτωμένο έγγραφο χρησιμοποιώντας FontReplacements

• Εφαρμόζεται μετά την ολοκλήρωση όλων των αντικαταστάσεων γραμματοσειρών

### Δείτε επίσης

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
