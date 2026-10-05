---
title: "μέθοδος get_possible_conversions"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Ανακτά τις πιθανές μετατροπές για το πηγαίο έγγραφο."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

Ανακτά τις πιθανές μετατροπές για το πηγαίο έγγραφο.

Το επιστρεφόμενο αντικείμενο παρέχει πρόσβαση σε όλες τις επιλογές μετατροπής, συμπεριλαμβανομένων των πρωτεύοντων και δευτερευόντων μορφών, και περιλαμβάνει μεταδεδομένα σχετικά με το αρχείο προέλευσης.

```python
def get_possible_conversions(self):
    ...
```

**Returns:** GroupDocs.Conversion.Fluent.PossibleConversions: An object containing the source description and collections of conversion formats.

### Παράδειγμα

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Δείτε επίσης
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
