---
title: "ιδιότητα check_excel_restriction"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Η ιδιότητα καθορίζει αν ελέγχονται οι περιορισμοί αρχείων Excel κατά την τροποποίηση αντικειμένων σχετικών με κελιά."
type: docs
url: /el/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

Η ιδιότητα καθορίζει αν ελέγχονται οι περιορισμοί αρχείων Excel κατά την τροποποίηση αντικειμένων σχετικών με κελιά.

Εάν είναι true, η προσπάθεια εισαγωγής μιας συμβολοσειράς μεγαλύτερης από 32 K θα προκαλέσει εξαίρεση. Εάν είναι false, η εισαγόμενη συμβολοσειρά γίνεται αποδεκτή, επιτρέποντας την πλήρη τιμή να εξαχθεί σε άλλες μορφές όπως CSV. Ωστόσο, η αποθήκευση του βιβλίου εργασίας ξανά σε μορφή Excel με τέτοιες μη έγκυρες τιμές μπορεί να προκαλέσει απρόσμενα σφάλματα.

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### Δείτε επίσης
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
