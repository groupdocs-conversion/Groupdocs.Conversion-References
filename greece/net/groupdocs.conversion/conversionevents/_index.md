---
title: "ConversionEvents"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Συγκεντρώνει χειριστές γεγονότων κύκλου ζωής της μετατροπής. Περνάτε μια παρουσία στο παράμετρο events των κατασκευαστών του Converter./converter ή στη μέθοδο fluent WithEvents. Προτιμήστε αυτό αντί για τις μεμονωμένες ιδιότητες χειριστών του ConverterSettings./convertersettings που είναι παρωχημένες."
type: docs
weight: 850
url: /el/net/groupdocs.conversion/conversionevents/
---
## ConversionEvents class

Συγκεντρώνει χειριστές γεγονότων κύκλου ζωής της μετατροπής. Περνάτε μια παρουσία στο παράμετρο `events` του κατασκευαστή [`Converter`](../converter) ή στη fluent `WithEvents` μέθοδο. Προτιμήστε αυτό αντί για τις μεμονωμένες ιδιότητες χειριστών του [`ConverterSettings`](../convertersettings), που είναι παρωχημένες.

```csharp
public sealed class ConversionEvents
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [ConversionEvents](conversionevents)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [OnCompressionCompleted](../../groupdocs.conversion/conversionevents/oncompressioncompleted) { get; set; } | Ενεργοποιείται όταν ολοκληρωθεί η συμπίεση της εξόδου της μετατροπής. Καλείται μόνο σε εκδόσεις που περιλαμβάνουν τη γραμμή συμπίεσης (LIB_ZIP). |
| [OnConversionCompleted](../../groupdocs.conversion/conversionevents/onconversioncompleted) { get; set; } | Ενεργοποιείται μία φορά όταν ολοκληρωθεί η εκτέλεση της μετατροπής, ανεξάρτητα από την επιτυχία ή την αποτυχία. |
| [OnConversionProgress](../../groupdocs.conversion/conversionevents/onconversionprogress) { get; set; } | Ενεργοποιείται περιοδικά με την πρόοδο της μετατροπής ως ποσοστό (0–100). |
| [OnConversionStarted](../../groupdocs.conversion/conversionevents/onconversionstarted) { get; set; } | Ενεργοποιείται μία φορά στην αρχή της εκτέλεσης της μετατροπής, πριν επεξεργαστεί οποιοδήποτε έγγραφο. |
| [OnDocumentConverted](../../groupdocs.conversion/conversionevents/ondocumentconverted) { get; set; } | Ενεργοποιείται μία φορά ανά πλήρη μετατροπή εγγράφου που ολοκληρώνεται επιτυχώς. |
| [OnDocumentFailed](../../groupdocs.conversion/conversionevents/ondocumentfailed) { get; set; } | Ενεργοποιείται μία φορά ανά πλήρη μετατροπή εγγράφου που αποτυγχάνει. |
| [OnFontSubstituted](../../groupdocs.conversion/conversionevents/onfontsubstituted) { get; set; } | Ενεργοποιείται όταν μια γραμματοσειρά που αναφέρεται από το πηγαίο έγγραφο δεν είναι διαθέσιμη και αντικαθίσταται (είτε από έναν κανόνα [`FontSubstitute`](../../groupdocs.conversion.contracts/fontsubstitute) που παρέχεται από τον πελάτη, είτε από την προεπιλεγμένη γραμματοσειρά που έχει ρυθμιστεί, είτε από την εσωτερική εναλλακτική λύση της γραμμής μετατροπής). |
| [OnPageConverted](../../groupdocs.conversion/conversionevents/onpageconverted) { get; set; } | Ενεργοποιείται μία φορά ανά σελίδα όταν μια μετατροπή ανά σελίδα ολοκληρώνεται επιτυχώς. |
| [OnPageFailed](../../groupdocs.conversion/conversionevents/onpagefailed) { get; set; } | Ενεργοποιείται μία φορά ανά σελίδα όταν μια μετατροπή ανά σελίδα αποτυγχάνει. |

### Δείτε επίσης

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
