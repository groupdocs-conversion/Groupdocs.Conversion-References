---
title: "CapResolutionToPageContent"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Όταν είναι ορισμένο, περιορίζει την ανάλυση απόδοσης PDF ανά σελίδα στην εγγενή ανάλυση raster της σελίδας, ώστε μια σελίδα να μην αποδίδεται ποτέ σε υψηλότερο DPI από αυτό που περιέχει η ενσωματωμένη εικόνα και εκδίδει τη σελίδα με τις εγγενείς μικρότερες διαστάσεις εικονοστοιχείων και το εγγενές DPI στην τελική έξοδο αντί να την επαναφουσκώνει στο ζητούμενο DPI. Επηρεάζονται μόνο οι σελίδες σάρωσης που κυριαρχούνται από εικόνα· οι σελίδες με κείμενο ή διανυσματικό περιεχόμενο δεν μαλακώνουν ποτέ και εκδίδονται στο ζητούμενο DPI. Παραλείπεται όταν έχει οριστεί ρητό έξοδο Widthgroupdocs.conversion.options.convert/imageconvertoptions/width ή Heightgroupdocs.conversion.options.convert/imageconvertoptions/height. Η προεπιλογή είναι false (χωρίς περιορισμό· κάθε σελίδα αποδίδεται και εκδίδεται στο ζητούμενο DPI)."
type: docs
weight: 40
url: /el/net/groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent/
---
## ImageConvertOptions.CapResolutionToPageContent property

Όταν είναι ορισμένο, περιορίζει την ανάλυση απόδοσης PDF ανά σελίδα στην εγγενή ανάλυση raster της σελίδας, ώστε μια σελίδα να μην αποδίδεται ποτέ σε υψηλότερο DPI από αυτό που περιέχει η ενσωματωμένη εικόνα, και εκδίδει τη σελίδα με τις εγγενείς (μικρότερες) διαστάσεις εικονοστοιχείων και το εγγενές DPI στην τελική έξοδο αντί να την επαναφουσκώνει στο ζητούμενο DPI. Επηρεάζονται μόνο οι σελίδες που κυριαρχούνται από εικόνα (σάρωση); οι σελίδες με κείμενο ή διανυσματικό περιεχόμενο δεν μαλακώνουν ποτέ και εκδίδονται στο ζητούμενο DPI. Παραλείπεται όταν έχει οριστεί ρητό έξοδο [`Width`](../width) ή [`Height`](../height). Η προεπιλογή είναι `false` (χωρίς περιορισμό· κάθε σελίδα αποδίδεται και εκδίδεται στο ζητούμενο DPI).

```csharp
public bool CapResolutionToPageContent { get; set; }
```

### Δείτε επίσης

* class [ImageConvertOptions](../../imageconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
