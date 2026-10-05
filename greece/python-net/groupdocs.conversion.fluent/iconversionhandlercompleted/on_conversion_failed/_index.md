---
title: "on_conversion_failed μέθοδος"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή εγγράφου αποτύχει."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Καταχωρεί μια κλήση επιστροφής (callback) που θα κληθεί όταν αποτύχει η μετατροπή εγγράφου. Η επανεκτέλεση αντικαθιστά οποιονδήποτε προηγουμένως ορισμένο χειριστή.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| on_failed | `Action[ConvertedContext, Exception]` | Callable[[GroupDocs.Conversion.Fluent.IConversionContext, Exception], Any] – μια ενέργεια για τη διαχείριση της αποτυχίας, λαμβάνοντας το πλαίσιο μετατροπής και την εξαίρεση που προκάλεσε την αποτυχία. |

**Returns:** IConversionHandlerCompleted – the current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Δείτε επίσης
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
