---
title: "μέθοδος compress"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Συμπιέζει τα αποτελέσματα της μετατροπής."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/compress/
is_root: false
weight: 1010
---


## compress {#options}

Συμπιέζει τα αποτελέσματα της μετατροπής.

Καταχωρίστε έναν χειριστή συμπιεσμένου‑ρεύματος στο στάδιο εισόδου μέσω [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (ορίζοντας `OnCompressionCompleted`) αντί να χρησιμοποιήσετε την παρωχημένη μέθοδο αλυσιδωτής ροής στην επιστρεφόμενη διεπαφή.

```python
def compress(self, options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Επιλογές μετατροπής συμπίεσης. |

**Returns:** Continuation that proceeds to `Convert`.

### Δείτε επίσης
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
