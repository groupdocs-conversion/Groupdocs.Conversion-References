---
title: "μέθοδος set_license"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Εφαρμόστε μια άδεια στην τρέχουσα διαδικασία."
type: docs
url: /el/python-net/groupdocs.conversion/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Εφαρμόστε μια άδεια στην τρέχουσα διαδικασία.

```python
def set_license(self, license_source):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| license_source |  | Είτε μια διαδρομή συμβολοσειράς προς ένα αρχείο ``.lic`` είτε ένα αναγνώσιμο αντικείμενο‑αρχείου που παρέχει τα byte της άδειας. Τα εισερχόμενα τύπου αρχείου γράφονται σε ένα προσωρινό αρχείο πριν περαστούν στη γέφυρα. |

| Εγείρει | Περιγραφή |
| :- | :- |
| `TypeError` | Εάν το ``license_source`` δεν είναι ούτε διαδρομή συμβολοσειράς ούτε αναγνώσιμο αντικείμενο‑αρχείου. |

### Δείτε επίσης
* class [`License`](/conversion/python-net/groupdocs.conversion/license/)
