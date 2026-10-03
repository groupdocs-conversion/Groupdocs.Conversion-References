---
title: "MarkdownOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές για μετατροπή σε τύπο αρχείου markdown."
type: docs
weight: 2010
url: /el/net/groupdocs.conversion.options.convert/markdownoptions/
---
## MarkdownOptions class

Επιλογές για μετατροπή σε τύπο αρχείου markdown.

```csharp
public sealed class MarkdownOptions : ValueObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MarkdownOptions](markdownoptions)() | Αρχικοποιεί νέο στιγμιότυπο της κλάσης [`MarkdownOptions`](../markdownoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.conversion.options.convert/markdownoptions/exportimagesasbase64) { get; set; } | Εξαγωγή εικόνων ως base64. Η προεπιλογή είναι αληθής. Αγνοείται όταν έχει οριστεί το [`ImageSavingCallback`](./imagesavingcallback). |
| [ImageSavingCallback](../../groupdocs.conversion.options.convert/markdownoptions/imagesavingcallback) { get; set; } | Η κλήση επιστροφής εκτελείται μία φορά ανά εικόνα κατά την αποθήκευση του Markdown. Επιτρέπει στον καλούντα να αποθηκεύει τις εικόνες εξωτερικά και να αντικαθιστά το ενσωματωμένο URI στο έγγραφο. Έχει προτεραιότητα έναντι του [`ExportImagesAsBase64`](./exportimagesasbase64) όταν δεν είναι null. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
