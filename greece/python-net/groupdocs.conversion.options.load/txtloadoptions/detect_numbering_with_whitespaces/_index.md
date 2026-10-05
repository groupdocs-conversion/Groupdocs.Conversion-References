---
title: "detect_numbering_with_whitespaces property"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Η ιδιότητα καθορίζει πώς αναγνωρίζονται τα στοιχεία αριθμημένης λίστας όταν μετατρέπεται ένα έγγραφο απλού κειμένου."
type: docs
url: /el/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

Η ιδιότητα καθορίζει πώς αναγνωρίζονται τα στοιχεία αριθμημένης λίστας όταν ένα έγγραφο απλού κειμένου μετατρέπεται. Η προεπιλεγμένη τιμή είναι True.

Εάν αυτή η επιλογή οριστεί σε False, ο αλγόριθμος αναγνώρισης λιστών εντοπίζει παραγράφους λίστας όταν οι αριθμοί λίστας τελειώνουν με τελεία, δεξιό αγκύλη ή σύμβολα κουκίδας (όπως \"•\", \"*\", \"-\" ή \"o\").

Εάν αυτή η επιλογή οριστεί σε True, τα κενά χρησιμοποιούνται επίσης ως διαχωριστικά αριθμών λίστας: ο αλγόριθμος αναγνώρισης λιστών για αρίθμηση στυλ Αραβικών (π.χ., 1., 1.1.2.) χρησιμοποιεί τόσο τα κενά όσο και το σύμβολο τελείας (\".\").

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### Δείτε επίσης
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
