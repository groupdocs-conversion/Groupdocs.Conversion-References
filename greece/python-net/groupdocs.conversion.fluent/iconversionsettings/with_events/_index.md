---
title: "μέθοδος with_events"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Καταχωρίζει χειριστές γεγονότων κύκλου ζωής μετατροπής σε μια συλλογή ConversionEvents που υπάρχει για τη διάρκεια ζωής του μετατροπέα και εκτελείται σε κάθε εκτέλεση μετατροπής."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/
is_root: false
weight: 1010
---


## with_events {#configure}

Καταχωρεί χειριστές γεγονότων κύκλου ζωής μετατροπής σε μια τσάντα [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) που διαρκεί για όλη τη διάρκεια ζωής του μετατροπέα και ενεργοποιείται σε κάθε εκτέλεση μετατροπής.

Βρίσκεται στο ίδιο στάδιο εισόδου με [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/). Πολλές κλήσεις συσσωρεύονται: η ίδια εσωτερική τσάντα περνά σε κάθε ενέργεια `configure`, έτσι οι χειριστές που ορίστηκαν σε προηγούμενες κλήσεις παραμένουν εκτός αν αντικατασταθούν από μια μεταγενέστερη.

```python
def with_events(self, configure):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Δράση που τροποποιεί την τσάντα συμβάντων. |

**Returns:** The source-selection stage so that `Load` may be chained.

### Δείτε επίσης
* class [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/)
