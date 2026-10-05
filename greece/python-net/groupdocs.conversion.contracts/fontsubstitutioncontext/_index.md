---
title: "FontSubstitutionContext κλάση"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Περιγράφει μια μοναδική αντικατάσταση γραμματοσειράς που συνέβη κατά τη φόρτωση ή την απόδοση ενός πηγαίου εγγράφου."
type: docs
url: /el/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

Περιγράφει μια μοναδική αντικατάσταση γραμματοσειράς που συνέβη κατά τη φόρτωση ή την απόδοση ενός πηγαίου εγγράφου.

Οι παρουσίες περνούν στο [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/).

Η FontSubstitutionContext τύπος εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | Αρχικοποιεί ένα νέο FontSubstitutionContext. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | Το όνομα της γραμματοσειράς που αναφέρεται από το πηγαίο έγγραφο αλλά δεν είναι διαθέσιμο στην αλυσίδα μετατροπής. |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | Το μήνυμα αντικατάστασης ακριβώς όπως αναφέρεται από τη γραμμή μετατροπής, κυριολεκτικά και αμετάφραστο. |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | Το όνομα αρχείου του πηγαίου εγγράφου που μετατρέπεται. Όταν η πηγή παρέχεται ως ροή που δεν είναι `io.RawIOBase`, αυτό περιέχει ένα παραγόμενο αναγνωριστικό αντί για πραγματικό όνομα αρχείου. |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | Το όνομα της γραμματοσειράς που χρησιμοποιείται ως υποκατάστατο. Μπορεί να είναι None για έγγραφα των οποίων η μηχανή αναφέρει την αντικατάσταση μόνο ως περιγραφικό κείμενο — σε αυτήν την περίπτωση διαβάστε [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/). |

### Δείτε επίσης
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
