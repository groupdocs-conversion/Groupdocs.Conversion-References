---
title: "PresentationConvertOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Περιγράφει τις επιλογές μετατροπής σε τύπο αρχείου Παρουσίασης."
type: docs
weight: 2170
url: /el/net/groupdocs.conversion.options.convert/presentationconvertoptions/
---
## PresentationConvertOptions class

Περιγράφει τις επιλογές μετατροπής σε τύπο αρχείου Παρουσίασης.

```csharp
public class PresentationConvertOptions : CommonConvertOptions<PresentationFileType>, 
    IPasswordConvertOptions, IZoomConvertOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PresentationConvertOptions](presentationconvertoptions)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [`PresentationConvertOptions`](../presentationconvertoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Ο επιθυμητός τύπος αρχείου στον οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Υλοποιεί [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Υλοποιεί [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Υλοποιεί [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Υλοποιεί [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/presentationconvertoptions/password) { get; set; } | Ορίστε αυτήν την ιδιότητα εάν θέλετε να προστατεύσετε το μετατρεπόμενο έγγραφο με κωδικό πρόσβασης. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Υλοποιεί [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/presentationconvertoptions/zoom) { get; set; } | Καθορίζει το επίπεδο ζουμ σε ποσοστό. Η προεπιλογή είναι 100. Το προεπιλεγμένο ζουμ υποστηρίζεται μέχρι το Microsoft Powerpoint 2010. Από το Microsoft Powerpoint 2013 το προεπιλεγμένο ζουμ δεν ορίζεται πλέον στο έγγραφο, αλλά φαίνεται ότι χρησιμοποιεί τον παράγοντα ζουμ του τελευταίου ανοιγμένου εγγράφου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία επιλογών. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PresentationFileType](../../groupdocs.conversion.filetypes/presentationfiletype)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
