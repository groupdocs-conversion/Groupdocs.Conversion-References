---
title: "TxtLoadOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για τη φόρτωση εγγράφων Txt."
type: docs
weight: 2870
url: /el/net/groupdocs.conversion.options.load/txtloadoptions/
---
## TxtLoadOptions class

Επιλογές για τη φόρτωση εγγράφων Txt.

```csharp
public sealed class TxtLoadOptions : LoadOptions, IPageMarginOptions, IPageSizeOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [TxtLoadOptions](txtloadoptions)() | Αρχικοποιεί νέο αντικείμενο της κλάσης [`TxtLoadOptions`](../txtloadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/txtloadoptions/defaultfont) { get; set; } | Γραμματοσειρά που θα χρησιμοποιηθεί κατά την απόδοση του περιεχομένου απλού κειμένου κατά τη μετατροπή. Δεδομένου ότι τα αρχεία TXT δεν περιέχουν πληροφορίες γραμματοσειράς, αυτή η ιδιότητα καθορίζει τη γραμματοσειρά εμφάνισης για το κειμενικό περιεχόμενο. Προεπιλογή: Arial 10pt. |
| [DetectNumberingWithWhitespaces](../../groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces) { get; set; } | Επιτρέπει τον καθορισμό του τρόπου αναγνώρισης των στοιχείων αριθμημένης λίστας όταν το έγγραφο απλού κειμένου μετατρέπεται. Η προεπιλεγμένη τιμή είναι true. |
| [Encoding](../../groupdocs.conversion.options.load/txtloadoptions/encoding) { get; set; } | Λαμβάνει ή ορίζει την κωδικοποίηση που θα χρησιμοποιηθεί κατά τη φόρτωση του εγγράφου Txt. Μπορεί να είναι null. Η προεπιλογή είναι null. |
| [Format](../../groupdocs.conversion.options.load/txtloadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. Είναι `null` μέχρι να οριστεί μια μορφή, έτσι ελέγξτε το για `null` αντί να το συγκρίνετε με [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), το οποίο ποτέ δεν ισούται. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εισαγόμενου εγγράφου. |
| [LeadingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/leadingspacesoptions) { get; set; } | Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης αρχικού διαστήματος. Η προεπιλεγμένη τιμή είναι [`ConvertToIndent`](../txtleadingspacesoptions/converttoindent). |
| [MarginSettings](../../groupdocs.conversion.options.load/txtloadoptions/marginsettings) { get; set; } | Ρυθμίσεις περιθωρίων σελίδας |
| [SizeSettings](../../groupdocs.conversion.options.load/txtloadoptions/sizesettings) { get; set; } | Ρυθμίσεις μεγέθους σελίδας |
| [TrailingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/trailingspacesoptions) { get; set; } | Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης τελικού διαστήματος. Η προεπιλεγμένη τιμή είναι [`Trim`](../txttrailingspacesoptions/trim). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Παρατηρήσεις

**Font Configuration for Plain Text:**

Δεδομένου ότι τα αρχεία TXT δεν περιέχουν πληροφορίες γραμματοσειράς, χρησιμοποιήστε το DefaultTextFont για να καθορίσετε

τη γραμματοσειρά για την απόδοση του περιεχομένου απλού κειμένου κατά τη μετατροπή.

### Δείτε επίσης

* class [LoadOptions](../loadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
