---
title: "μέθοδος with_events"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Καταχωρίστε χειριστές γεγονότων κύκλου ζωής μετατροπής σε μια συλλογή ConversionEvents που διαρκεί για όλη τη διάρκεια ζωής του μετατροπέα και ενεργοποιείται σε κάθε εκτέλεση μετατροπής."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Καταχωρίστε χειριστές συμβάντων κύκλου ζωής μετατροπής σε μια τσάντα [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) που διαρκεί για όλη τη διάρκεια ζωής του μετατροπέα και ενεργοποιείται σε κάθε εκτέλεση μετατροπής.

Μπορεί να κληθεί πριν ή μετά το [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/).
Πολλαπλές κλήσεις συσσωρεύονται: η ίδια εσωτερική συλλογή περνάει σε κάθε ενέργεια `configure`, έτσι οι χειριστές που ορίζονται σε προηγούμενες κλήσεις παραμένουν εκτός αν αντικατασταθούν από μια μεταγενέστερη.

```python
def with_events(self, configure):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Δράση που τροποποιεί την τσάντα συμβάντων. |

**Returns:** This stage so that further entry-stage calls or `Load` may be chained.

### Δείτε επίσης
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
