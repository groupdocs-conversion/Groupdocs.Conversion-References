---
title: "IConversionFrom"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ρυθμίστε την πηγή για τη μετατροπή"
type: docs
weight: 1440
url: /el/net/groupdocs.conversion.fluent/iconversionfrom/
---
## IConversionFrom interface

Ρυθμίστε την πηγή για τη μετατροπή

```csharp
public interface IConversionFrom
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_1)(Func&lt;Stream&gt;) | Ορίστε τη ροή του πηγαίου εγγράφου |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load)(Func&lt;Stream[]&gt;) | Ορίστε τον πίνακα ροών πηγαίων εγγράφων |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_2)(string) | Ορίστε το fileName του πηγαίου εγγράφου |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_3)(string[]) | Ορίστε τον πίνακα πηγαίων εγγράφων |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionfrom/withevents)(Action&lt;ConversionEvents&gt;) | Καταχωρίστε τους χειριστές συμβάντων κύκλου ζωής της μετατροπής σε μια τσάντα [`ConversionEvents`](../../groupdocs.conversion/conversionevents) που διαρκεί για τη διάρκεια του μετατροπέα και ενεργοποιείται σε κάθε εκτέλεση μετατροπής. Μπορεί να κληθεί πριν ή μετά το [`WithSettings`](../iconversionsettings/withsettings). Οι πολλαπλές κλήσεις συσσωρεύονται: η ίδια εσωτερική τσάντα περνά σε κάθε ενέργεια *configure*, έτσι οι χειριστές που ορίστηκαν σε προηγούμενες κλήσεις παραμένουν εκτός αν αντικατασταθούν από μια μεταγενέστερη. |

### Δείτε επίσης

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
