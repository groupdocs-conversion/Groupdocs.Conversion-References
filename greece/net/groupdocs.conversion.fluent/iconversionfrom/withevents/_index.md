---
title: "WithEvents"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Καταχωρίστε χειριστές γεγονότων κύκλου ζωής μετατροπής σε μια τσάντα ConversionEventsgroupdocs.conversion/conversionevents που διαρκεί για τη διάρκεια ζωής του μετατροπέα και ενεργοποιείται σε κάθε εκτέλεση μετατροπής. Μπορεί να κληθεί πριν ή μετά το WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings. Πολλές κλήσεις συσσωρεύουν την ίδια εσωτερική τσάντα που περνά σε κάθε δράση configure, ώστε οι χειριστές που ορίστηκαν σε προηγούμενες κλήσεις να παραμείνουν εκτός αν αντικατασταθούν από μια μεταγενέστερη."
type: docs
weight: 20
url: /el/net/groupdocs.conversion.fluent/iconversionfrom/withevents/
---
## IConversionFrom.WithEvents method

Καταχωρίστε χειριστές γεγονότων κύκλου ζωής μετατροπής σε μια τσάντα [`ConversionEvents`](../../../groupdocs.conversion/conversionevents) που διαρκεί για τη διάρκεια ζωής του μετατροπέα και ενεργοποιείται σε κάθε εκτέλεση μετατροπής. Μπορεί να κληθεί πριν ή μετά το [`WithSettings`](../../iconversionsettings/withsettings). Πολλές κλήσεις συσσωρεύουν: η ίδια εσωτερική τσάντα περνά σε κάθε δράση *configure*, ώστε οι χειριστές που ορίστηκαν σε προηγούμενες κλήσεις να παραμείνουν εκτός αν αντικατασταθούν από μια μεταγενέστερη.

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| configure | Action`1 | Δράση που τροποποιεί την τσάντα γεγονότων. |

### Τιμή επιστροφής

Αυτό το στάδιο ώστε περαιτέρω κλήσεις εισόδου ή `Load` να μπορούν να συνδεθούν.

### Δείτε επίσης

* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
