---
title: "on_conversion_failed μέθοδος"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή εγγράφου αποτύχει."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή εγγράφου αποτύχει.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Κλήσιμο που διαχειρίζεται την αποτυχία, λαμβάνοντας το πλαίσιο μετατροπής και την εξαίρεση που προκάλεσε την αποτυχία. |

**Returns:** `IConversionOptionsOrHandlerSetup`: Interface to continue conversion building, allowing only OnConversionCompleted or Convert/Compress.

### Δείτε επίσης
* class [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/)
