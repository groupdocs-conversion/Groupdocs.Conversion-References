---
title: "ιδιότητα cap_resolution_to_page_content"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Η ιδιότητα περιορίζει την ανάλυση απόδοσης PDF ανά σελίδα στην εγγενή ανάλυση raster της σελίδας, αποτρέποντας την απόδοση σε υψηλότερο DPI από την ενσωματωμένη εικόνα και εκδίδοντας τη σελίδα στην εγγενή (μικρότερη) της…"
type: docs
url: /el/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

Η ιδιότητα περιορίζει την ανάλυση απόδοσης PDF ανά σελίδα στην εγγενή ανάλυση raster της σελίδας, αποτρέποντας την απόδοση σε υψηλότερο DPI από την ενσωματωμένη εικόνα και εκδίδοντας τη σελίδα στις εγγενείς (μικρότερες) διαστάσεις pixel και DPI στην τελική έξοδο.

Μόνο οι σελίδες που κυριαρχούνται από εικόνα (σάρωση) επηρεάζονται· οι σελίδες με κείμενο ή διανυσματικό περιεχόμενο δεν μαλακώνουν ποτέ και εκδίδονται στο ζητούμενο DPI. Ο περιορισμός αγνοείται όταν ορίζεται μια ρητή έξοδος [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) ή [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/). Η προεπιλογή είναι False (χωρίς περιορισμό· κάθε σελίδα αποδίδεται και εκδίδεται στο ζητούμενο DPI).

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### Δείτε επίσης
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
