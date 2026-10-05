---
title: "μέθοδος on_conversion_completed"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Λαμβάνει τη ροή του μετατρεπόμενου εγγράφου και ενεργοποιείται μόνο εάν έχει οριστεί το ConvertTo(string fileName) ή το ConvertTo(convertedStreamProvider)."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversioncompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_file_stream}

Λαμβάνει τη ροή του μετατρεπόμενου εγγράφου και ενεργοποιείται μόνο εάν `ConvertTo(string fileName)` ή `ConvertTo(convertedStreamProvider)` έχει οριστεί.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Πάροχος ροής μετατρεπόμενου εγγράφου. |

**Returns:** Interface to continue conversion building.

### Δείτε επίσης
* class [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/)
