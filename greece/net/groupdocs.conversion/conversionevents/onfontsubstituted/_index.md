---
title: "OnFontSubstituted"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ενεργοποιείται όταν μια γραμματοσειρά που αναφέρεται από το πηγαίο έγγραφο δεν είναι διαθέσιμη και αντικαθίσταται είτε από έναν πελάτη‑παρεχόμενο κανόνα FontSubstitutegroupdocs.conversion.contracts/fontsubstitute, είτε από την προρυθμισμένη προεπιλεγμένη γραμματοσειρά, είτε από το εσωτερικό fallback των αγωγών μετατροπής."
type: docs
weight: 80
url: /el/net/groupdocs.conversion/conversionevents/onfontsubstituted/
---
## ConversionEvents.OnFontSubstituted property

Ενεργοποιείται όταν μια γραμματοσειρά που αναφέρεται από το πηγαίο έγγραφο δεν είναι διαθέσιμη και αντικαθίσταται (είτε από έναν πελάτη‑παρεχόμενο κανόνα [`FontSubstitute`](../../../groupdocs.conversion.contracts/fontsubstitute), είτε από την προρυθμισμένη προεπιλεγμένη γραμματοσειρά, είτε από το εσωτερικό fallback του αγωγού μετατροπής).

```csharp
public Action<FontSubstitutionContext> OnFontSubstituted { get; set; }
```

### Παρατηρήσεις

Το γεγονός αφαιρεί τις διπλές εγγραφές ανά `(SourceFileName, OriginalFontName)` μέσα σε μία κλήση `Converter.Convert(...)` — οι συνδρομητές λαμβάνουν το πολύ μία ειδοποίηση ανά ελλιπή γραμματοσειρά ανά πηγαίο έγγραφο. Εκτελείται συγχρονισμένα στο νήμα μετατροπής. Δεν ενεργοποιείται για μετατροπές εικόνας.

Για έγγραφα παρουσίασης, η αντικατάσταση γραμματοσειράς εντοπίζεται μόνο στα Windows, επειδή η μηχανή το επιλύει μέσω αντιστοίχισης γραμματοσειρών ειδικής πλατφόρμας που δεν είναι διαθέσιμη σε άλλα λειτουργικά συστήματα.

### Δείτε επίσης

* class [FontSubstitutionContext](../../../groupdocs.conversion.contracts/fontsubstitutioncontext)
* class [ConversionEvents](../../conversionevents)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
