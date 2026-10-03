---
title: "EmailLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων email."
type: docs
weight: 2500
url: /el/net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

Επιλογές για τη φόρτωση εγγράφων email.

```csharp
public sealed class EmailLoadOptions : LoadOptions, ICustomCssStyleOptions, 
    IDocumentsContainerLoadOptions, IFontSubstituteLoadOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [`EmailLoadOptions`](../emailloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/attachmenticons) { get; set; } | Λαμβάνει ή ορίζει τη λίστα των εικονιδίων συνημμένων. Η λίστα μπορεί να προσαρμοστεί ώστε να παρέχει συγκεκριμένα εικονίδια για διαφορετικούς τύπους αρχείων. Από προεπιλογή, περιέχει κοινά εικονίδια τύπων αρχείων. |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | Υλοποιεί το [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned). Η προεπιλογή είναι true |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | Υλοποιεί [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Η προεπιλογή είναι true |
| [CustomCssStyle](../../groupdocs.conversion.options.load/emailloadoptions/customcssstyle) { get; set; } | Υλοποιεί [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [DefaultFont](../../groupdocs.conversion.options.load/emailloadoptions/defaultfont) { get; set; } | Προεπιλεγμένη γραμματοσειρά για το έγγραφο email. Η παρακάτω γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά. |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | Υλοποιεί [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Προεπιλογή: 1 |
| [DisplayAttachments](../../groupdocs.conversion.options.load/emailloadoptions/displayattachments) { get; set; } | Επιλογή εμφάνισης ή απόκρυψης συνημμένων στην κεφαλίδα. Προεπιλογή: true. |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | Επιλογή εμφάνισης ή απόκρυψης της διεύθυνσης email "Bcc". Προεπιλογή: false. |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | Επιλογή εμφάνισης ή απόκρυψης της διεύθυνσης email "Cc". Προεπιλογή: false. |
| [DisplayEmailAddresses](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddresses) { get; set; } | Επιλογή ελέγχου εάν οι διευθύνσεις email εμφανίζονται δίπλα στα ονόματα. Παράδειγμα: "John Doe &lt;john.doe@sample.com&gt;" ή μόνο "John Doe." Προεπιλογή: true. |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | Επιλογή εμφάνισης ή απόκρυψης της διεύθυνσης email "from". Προεπιλογή: true. |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | Επιλογή εμφάνισης ή απόκρυψης της κεφαλίδας του email. Προεπιλογή: true. |
| [DisplaySent](../../groupdocs.conversion.options.load/emailloadoptions/displaysent) { get; set; } | Επιλογή εμφάνισης ή απόκρυψης της ημερομηνίας/ώρας αποστολής στην κεφαλίδα. Προεπιλογή: true. |
| [DisplaySubject](../../groupdocs.conversion.options.load/emailloadoptions/displaysubject) { get; set; } | Επιλογή εμφάνισης ή απόκρυψης του θέματος στην κεφαλίδα. Προεπιλογή: true. |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | Επιλογή εμφάνισης ή απόκρυψης της διεύθυνσης email "to". Προεπιλογή: true. |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | Η αντιστοίχηση μεταξύ του μηνύματος email [`EmailField`](../emailfield) και της αναπαράστασης κειμένου πεδίου |
| [FontSubstitutes](../../groupdocs.conversion.options.load/emailloadoptions/fontsubstitutes) { get; set; } | Λίστα υποκατάστατων γραμματοσειρών. |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | Τύπος αρχείου εισαγόμενου εγγράφου. Είναι `null` μέχρι να οριστεί μια μορφή, έτσι ελέγξτε το για `null` αντί να το συγκρίνετε με [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), το οποίο ποτέ δεν ισούται. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| [MarginSettings](../../groupdocs.conversion.options.load/emailloadoptions/marginsettings) { get; set; } | Ρυθμίσεις περιθωρίων σελίδας |
| [OrientationSettings](../../groupdocs.conversion.options.load/emailloadoptions/orientationsettings) { get; set; } | Ρυθμίσεις προσανατολισμού σελίδας |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/emailloadoptions/pagelayoutoptions) { get; set; } | Υλοποιεί το [`PageLayoutOptions`](../ipagelayoutoptions/pagelayoutoptions) |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | Ορίζει εάν χρειάζεται να διατηρηθεί η αρχική συμβολοσειρά ημερομηνίας κεφαλίδας στο μήνυμα email κατά την αποθήκευση ή όχι (Η προεπιλεγμένη τιμή είναι true) |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | Χρόνος λήξης για τη φόρτωση εξωτερικών πόρων |
| [SizeSettings](../../groupdocs.conversion.options.load/emailloadoptions/sizesettings) { get; set; } | Ρυθμίσεις μεγέθους σελίδας |
| [SkipExternalResources](../../groupdocs.conversion.options.load/emailloadoptions/skipexternalresources) { get; set; } | Υλοποιεί [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | Λαμβάνει ή ορίζει τη διαφορά ώρας (UTC) για τις ημερομηνίες των μηνυμάτων. Αυτή η ιδιότητα ορίζει τη διαφορά ζώνης ώρας μεταξύ της τοπικής ώρας και του UTC. |
| [UseDefaultAttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/usedefaultattachmenticons) { get; set; } | Λαμβάνει ή ορίζει εάν θα χρησιμοποιηθούν τα προεπιλεγμένα εικονίδια συνημμένων. Προεπιλογή: true. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/emailloadoptions/whitelistedresources) { get; set; } | Υλοποιεί [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [LoadOptions](../loadoptions)
* interface [ICustomCssStyleOptions](../icustomcssstyleoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IPageLayoutOptions](../ipagelayoutoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
