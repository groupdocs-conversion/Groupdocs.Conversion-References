---
title: EmailLoadOptions
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Επιλογές για φόρτωση εγγράφων email.
type: docs
weight: 2110
url: /el/net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

Επιλογές για φόρτωση εγγράφων email.

```csharp
public sealed class EmailLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | Αρχικοποιεί νέα παρουσία του[`EmailLoadOptions`](../emailloadoptions) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | Επιλογή για να ελέγξετε εάν τα έγγραφα που ανήκουν στο κοντέινερ εγγράφων πρέπει να μετατραπούν |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | Επιλογή ελέγχου εάν το ίδιο το κοντέινερ εγγράφων πρέπει να μετατραπεί Εάν αυτή η ιδιότητα είναι αληθής, το κοντέινερ εγγράφων θα είναι το πρώτο έγγραφο που έχει μετατραπεί |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | Επιλογή για τον έλεγχο πόσων επιπέδων σε βάθος θα πραγματοποιηθεί η μετατροπή |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | Επιλογή εμφάνισης ή απόκρυψης της διεύθυνσης email "Κρυφή κοινοποίηση". Προεπιλογή: false. |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | Επιλογή εμφάνισης ή απόκρυψης της διεύθυνσης email "Κοιν". Προεπιλογή: false. |
| [DisplayEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddress) { get; set; } | Επιλογή εμφάνισης ή απόκρυψης διεύθυνσης email. Προεπιλογή: true. |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | Επιλογή εμφάνισης ή απόκρυψης διεύθυνσης email "από". Προεπιλογή: true. |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | Επιλογή εμφάνισης ή απόκρυψης της κεφαλίδας του email. Προεπιλογή: true. |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | Επιλογή εμφάνισης ή απόκρυψης της διεύθυνσης email "προς". Προεπιλογή: true. |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | Η αντιστοίχιση μεταξύ μηνυμάτων email[`EmailField`](../emailfield) και αναπαράσταση κειμένου πεδίου |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | Τύπος αρχείου εγγράφου εισαγωγής. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εγγράφου εισαγωγής. |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | Καθορίζει εάν χρειάζεται να διατηρηθεί η αρχική συμβολοσειρά κεφαλίδας ημερομηνίας στο μήνυμα αλληλογραφίας κατά την αποθήκευση ή όχι (Η προεπιλεγμένη τιμή είναι αληθής) |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | Χρονικό όριο για τη φόρτωση εξωτερικών πόρων |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | Λαμβάνει ή ορίζει τη μετατόπιση Συντονισμένης Παγκόσμιας Ώρας (UTC) για τις ημερομηνίες του μηνύματος. Αυτή η ιδιότητα ορίζει τη διαφορά ζώνης ώρας, μεταξύ της τοπικής ώρας και της ώρας UTC. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Εξυπηρετεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* χώρος ονομάτων [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* συνέλευση [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
