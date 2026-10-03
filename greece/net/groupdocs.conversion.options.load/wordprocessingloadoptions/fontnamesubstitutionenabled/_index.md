---
title: "FontNameSubstitutionEnabled"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Αντικαθιστά αυτόματα τις ελλιπείς γραμματοσειρές βάσει του ονόματος γραμματοσειράς. Προεπιλογή ψευδής."
type: docs
weight: 140
url: /el/net/groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled/
---
## WordProcessingLoadOptions.FontNameSubstitutionEnabled property

Αντικαθιστά αυτόματα τις ελλιπείς γραμματοσειρές βάσει του ονόματος γραμματοσειράς. Προεπιλογή: false.

```csharp
public bool FontNameSubstitutionEnabled { get; set; }
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
