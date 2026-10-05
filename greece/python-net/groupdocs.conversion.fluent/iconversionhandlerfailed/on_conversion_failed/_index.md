---
title: "on_conversion_failed μέθοδος"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή εγγράφου αποτύχει."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/on_conversion_failed/
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

**Returns:** The flat handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### Δείτε επίσης
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
