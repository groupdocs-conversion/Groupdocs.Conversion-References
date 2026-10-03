---
title: "WithEvents"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Καταχωρίστε χειριστές συμβάντων κύκλου ζωής μετατροπής σε μια τσάντα ConversionEventsgroupdocs.conversion/conversionevents που ζει για τη διάρκεια ζωής του μετατροπέα και ενεργοποιείται σε κάθε εκτέλεση μετατροπής. Βρίσκεται στο ίδιο στάδιο εισόδου με το WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings. Πολλές κλήσεις συσσωρεύουν την ίδια εσωτερική τσάντα που περνιέται σε κάθε ενέργεια *configure*, ώστε οι χειριστές που ορίζονται σε προηγούμενες κλήσεις να παραμένουν εκτός αν αντικατασταθούν από μια μεταγενέστερη."
type: docs
weight: 10
url: /el/net/groupdocs.conversion.fluent/iconversionsettings/withevents/
---
## IConversionSettings.WithEvents method

Καταχωρίστε χειριστές συμβάντων κύκλου ζωής μετατροπής σε μια τσάντα [`ConversionEvents`](../../../groupdocs.conversion/conversionevents) που ζει για τη διάρκεια ζωής του μετατροπέα και ενεργοποιείται σε κάθε εκτέλεση μετατροπής. Βρίσκεται στο ίδιο στάδιο εισόδου με το [`WithSettings`](../withsettings). Πολλές κλήσεις συσσωρεύουν: η ίδια εσωτερική τσάντα περνιέται σε κάθε ενέργεια *configure*, ώστε οι χειριστές που ορίζονται σε προηγούμενες κλήσεις να παραμένουν εκτός αν αντικατασταθούν από μια μεταγενέστερη.

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| configure | Action`1 | Δράση που τροποποιεί την τσάντα γεγονότων. |

### Τιμή επιστροφής

Το στάδιο επιλογής πηγής ώστε το `Load` να μπορεί να αλυσοδεθεί.

### Δείτε επίσης

* interface [IConversionFrom](../../iconversionfrom)
* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionSettings](../../iconversionsettings)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
