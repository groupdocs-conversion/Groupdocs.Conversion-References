---
title: "μέθοδος on_conversion_completed"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Λαμβάνει το ροή του μετατρεπόμενου εγγράφου."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

Λαμβάνει τη ροή του μετατρεπόμενου εγγράφου. Ενεργοποιείται μόνο εάν έχει οριστεί το `ConvertTo(string fileName)` ή το `ConvertTo(convertedStreamProvider)`.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | Πάροχος ροής μετατρεπόμενου εγγράφου (`ConvertedContext`). |

**Returns:** Interface to continue conversion building.

### Δείτε επίσης
* class [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/)
