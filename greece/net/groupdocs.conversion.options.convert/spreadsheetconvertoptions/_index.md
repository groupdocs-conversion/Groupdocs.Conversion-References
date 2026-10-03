---
title: "SpreadsheetConvertOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές μετατροπής σε τύπο αρχείου Φύλλου Υπολογισμού."
type: docs
weight: 2240
url: /el/net/groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
## SpreadsheetConvertOptions class

Επιλογές μετατροπής σε τύπο αρχείου Φύλλου Υπολογισμού.

```csharp
public class SpreadsheetConvertOptions : CommonConvertOptions<SpreadsheetFileType>, 
    IPasswordConvertOptions, IZoomConvertOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SpreadsheetConvertOptions](spreadsheetconvertoptions)() | Αρχικοποιεί νέα παρουσία της κλάσης [`SpreadsheetConvertOptions`](../spreadsheetconvertoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Encoding](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/encoding) { get; set; } | Καθορίζει την κωδικοποίηση που θα χρησιμοποιηθεί κατά τη μετατροπή σε μορφές διαχωρισμένων. |
| [Format](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/format) { get; set; } | Ο επιθυμητός τύπος αρχείου στο οποίο πρέπει να μετατραπεί το έγγραφο εισόδου. (2 ιδιότητες) |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Υλοποιεί [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Υλοποιεί [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Υλοποιεί [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Υλοποιεί [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/password) { get; set; } | Ορίστε αυτήν την ιδιότητα εάν θέλετε να προστατεύσετε το μετατρεπόμενο έγγραφο με κωδικό πρόσβασης. |
| [Separator](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/separator) { get; set; } | Καθορίζει το διαχωριστικό που θα χρησιμοποιηθεί κατά τη μετατροπή σε μορφές διαχωρισμένων. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Υλοποιεί [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/zoom) { get; set; } | Καθορίζει το επίπεδο ζουμ σε ποσοστό. Η προεπιλογή είναι 100. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία επιλογών. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [SpreadsheetFileType](../../groupdocs.conversion.filetypes/spreadsheetfiletype)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
