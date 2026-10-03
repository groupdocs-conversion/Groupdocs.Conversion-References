---
title: "DefaultFont"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει τη προεπιλεγμένη γραμματοσειρά για ένα έγγραφο WordProcessing."
type: docs
weight: 90
url: /el/net/groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont/
---
## WordProcessingLoadOptions.DefaultFont property

Ορίζει τη προεπιλεγμένη γραμματοσειρά για ένα έγγραφο WordProcessing.

```csharp
public string DefaultFont { get; set; }
```

### Παρατηρήσεις

**Note:** The order of substitution is as follows:

1) Αντικαθιστά αυτόματα τις ελλιπείς γραμματοσειρές βάσει του ονόματος γραμματοσειράς (εάν είναι ενεργό).

2) Αντικαθιστά αυτόματα τις ελλιπείς γραμματοσειρές βάσει του FontConfig (εάν είναι ενεργό).

3) Αντικαθιστά τις ελλιπείς γραμματοσειρές βάσει του FontSubstitutes (εάν έχει οριστεί).

4) Αντικαθιστά αυτόματα τις ελλιπείς γραμματοσειρές βάσει του FontInfo (εάν είναι ενεργό).

5) Αντικαθιστά τις ελλιπείς γραμματοσειρές βάσει του DefaultFont (εάν έχει οριστεί).

### Δείτε επίσης

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
