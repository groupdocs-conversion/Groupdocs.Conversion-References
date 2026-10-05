---
title: "μέθοδος compress"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Συμπιέζει τα αποτελέσματα της μετατροπής χρησιμοποιώντας τις καθορισμένες επιλογές."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/compress/
is_root: false
weight: 1010
---


## compress {#options}

Συμπιέζει τα αποτελέσματα της μετατροπής χρησιμοποιώντας τις καθορισμένες επιλογές.

Καλέστε αυτή τη μέθοδο για να συμπιέσετε τα αποτελέσματα της μετατροπής. Καταχωρίστε έναν χειριστή συμπιεσμένου‑ροής στο στάδιο εισόδου μέσω [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (ρυθμίζοντας `OnCompressionCompleted`) αντί μέσω της παρωχημένης μεθόδου αλυσίδας fluent στο επιστρεφόμενο interface.

```python
def compress(self, options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Επιλογές μετατροπής συμπίεσης. |

**Returns:** Continuation that proceeds to `Convert`.

### Δείτε επίσης
* class [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/)
