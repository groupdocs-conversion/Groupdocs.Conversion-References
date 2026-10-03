---
title: "EmailConvertOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για μετατροπή σε τύπο αρχείου Ηλεκτρονική αλληλογραφία."
type: docs
weight: 1800
url: /el/net/groupdocs.conversion.options.convert/emailconvertoptions/
---
## EmailConvertOptions class

Επιλογές για μετατροπή σε τύπο αρχείου Ηλεκτρονική αλληλογραφία.

```csharp
public class EmailConvertOptions : ConvertOptions<EmailFileType>
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [EmailConvertOptions](emailconvertoptions)() | Αρχικοποιεί νέα παρουσία της κλάσης [`EmailConvertOptions`](../emailconvertoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AttachmentContentHandler](../../groupdocs.conversion.options.convert/emailconvertoptions/attachmentcontenthandler) { get; set; } | Ένας αντιπρόσωπος για τη διαχείριση προσαρμοσμένης επεξεργασίας συνημμένων email. Ο αντιπρόσωπος λαμβάνει το όνομα του συνημμένου, τον τύπο περιεχομένου και το αρχικό ρεύμα του συνημμένου ως παραμέτρους και επιστρέφει το τροποποιημένο ρεύμα του συνημμένου. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Ο επιθυμητός τύπος αρχείου στον οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Υλοποιεί [`Format`](../iconvertoptions/format) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία επιλογών. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [EmailFileType](../../groupdocs.conversion.filetypes/emailfiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
