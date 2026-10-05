---
title: "μέθοδος compress"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Συμπιέζει τα αποτελέσματα της μετατροπής· καταχωρίστε έναν χειριστή συμπιεσμένου‑ροής στο στάδιο εισόδου μέσω IConversionSettings.withevents (ρύθμιση OnCompressionCompleted) αντί να χρησιμοποιήσετε την παρωχημένη fluent…"
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

Συμπιέζει τα αποτελέσματα της μετατροπής· καταχωρίστε έναν χειριστή συμπιεσμένου‑ρεύματος στο αρχικό στάδιο μέσω του [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (ορίζοντας το `OnCompressionCompleted`) αντί να χρησιμοποιήσετε τη παρωχημένη μέθοδο ευέλικτης αλυσίδας.

```python
def compress(self, options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Επιλογές μετατροπής συμπίεσης. |

**Returns:** Continuation that proceeds to `Convert`.

### Δείτε επίσης
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
