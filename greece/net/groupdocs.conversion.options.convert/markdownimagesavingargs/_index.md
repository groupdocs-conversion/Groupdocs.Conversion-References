---
title: "MarkdownImageSavingArgs"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Παράμετροι που περνιούνται στο ImageSaving./imarkdownimagesavingcallback/imagesaving."
type: docs
weight: 2000
url: /el/net/groupdocs.conversion.options.convert/markdownimagesavingargs/
---
## MarkdownImageSavingArgs class

Παράμετροι που περνιούνται στο [`ImageSaving`](../imarkdownimagesavingcallback/imagesaving).

```csharp
public sealed class MarkdownImageSavingArgs
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ImageFileName](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagefilename) { get; set; } | Όνομα αρχείου (ή ταυτότητα placeholder) ενσωματωμένο ως URI εικόνας στην έξοδο Markdown. Αναθέστε για να ξαναγράψετε το URI. |
| [ImageStream](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagestream) { get; set; } | Ροή προορισμού στην οποία ο μετατροπέας θα γράψει τα byte της εικόνας μετά την επιστροφή αυτής της κλήσης. Αντικαταστήστε την με τη δική σας ροή εγγραφής (π.χ. ένα FileStream για αποθήκευση στο δίσκο ή ένα MemoryStream που σκοπεύετε να διαβάσετε αργότερα). |
| [KeepImageStreamOpen](../../groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen) { get; set; } | Όταν είναι false (προεπιλογή), ο μετατροπέας κλείνει το [`ImageStream`](./imagestream) μετά τη γραφή — τυπικό για αντικαταστάσεις FileStream που πρέπει να αδειάσουν στο δίσκο. Ορίστε σε true για να διατηρήσετε τη ροή ανοιχτή μετά την ολοκλήρωση της μετατροπής (συνηθισμένο για ένα MemoryStream που σκοπεύετε να διαβάσετε μόνοι σας); ο καλών τότε είναι υπεύθυνος για την απελευθέρωση. |

### Δείτε επίσης

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
