---
title: "IConversionSettings"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ρυθμίστε τις ρυθμίσεις μετατροπής ή τα συμβάντα στο στάδιο εισόδου πριν από το Load."
type: docs
weight: 1540
url: /el/net/groupdocs.conversion.fluent/iconversionsettings/
---
## IConversionSettings interface

Ρυθμίστε τις ρυθμίσεις μετατροπής ή τα συμβάντα στο αρχικό στάδιο (πριν το `Load`).

```csharp
public interface IConversionSettings
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionsettings/withevents)(Action&lt;ConversionEvents&gt;) | Καταχωρίστε τους χειριστές συμβάντων κύκλου ζωής μετατροπής σε μια τσάντα [`ConversionEvents`](../../groupdocs.conversion/conversionevents) που διαρκεί για όλη τη διάρκεια ζωής του μετατροπέα και ενεργοποιείται σε κάθε εκτέλεση μετατροπής. Βρίσκεται στο ίδιο στάδιο εισόδου με το [`WithSettings`](./withsettings). Οι πολλαπλές κλήσεις συσσωρεύονται: η ίδια εσωτερική τσάντα περνά σε κάθε ενέργεια *configure*, έτσι οι χειριστές που ορίστηκαν σε προηγούμενες κλήσεις παραμένουν εκτός εάν αντικατασταθούν από μια μεταγενέστερη. |
| [WithSettings](../../groupdocs.conversion.fluent/iconversionsettings/withsettings)(Func&lt;ConverterSettings&gt;) | Ορίστε τις ρυθμίσεις του μετατροπέα |

### Δείτε επίσης

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
