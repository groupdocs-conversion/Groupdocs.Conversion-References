---
title: "Κλάση ConversionEvents"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Συγκεντρώνει τους διαχειριστές γεγονότων του κύκλου ζωής της μετατροπής."
type: docs
url: /el/python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

Συγκεντρώνει τους διαχειριστές γεγονότων του κύκλου ζωής της μετατροπής.

Περάστε μια παρουσία στον κατασκευαστή του [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) στη παράμετρο `events` ή στη ρευστή μέθοδο `WithEvents`.

Προτιμήστε αυτό αντί για τις μεμονωμένες ιδιότητες χειριστή του [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/), που είναι παρωχημένες.

Ο τύπος ConversionEvents εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | Το συμβάν που ενεργοποιείται όταν ολοκληρωθεί η συμπίεση της εξόδου της μετατροπής. Καλείται μόνο σε εκδόσεις που περιλαμβάνουν τη γραμμή συμπίεσης (LIB_ZIP). |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | Το γεγονός που ενεργοποιείται μία φορά όταν ολοκληρωθεί η εκτέλεση της μετατροπής, ανεξάρτητα από την επιτυχία ή την αποτυχία. |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | Η πρόοδος της μετατροπής ως ποσοστό (0–100), ενεργοποιείται περιοδικά. |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | Το γεγονός που ενεργοποιείται μία φορά στην αρχή της εκτέλεσης της μετατροπής, πριν επεξεργαστεί οποιοδήποτε έγγραφο. |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | Το γεγονός ενεργοποιείται μία φορά ανά πλήρη μετατροπή εγγράφου που ολοκληρώνεται επιτυχώς. |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | Το γεγονός ενεργοποιείται μία φορά ανά πλήρη μετατροπή εγγράφου που αποτυγχάνει. |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | Το γεγονός ενεργοποιείται όταν μια γραμματοσειρά που αναφέρεται από το πηγαίο έγγραφο δεν είναι διαθέσιμη και αντικαθίσταται (είτε από έναν προσαρμοσμένο κανόνα [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/), είτε από την προρυθμισμένη προεπιλεγμένη γραμματοσειρά, είτε από την εσωτερική εναλλακτική λύση της γραμμής μετατροπής). |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | Το γεγονός ενεργοποιείται μία φορά ανά σελίδα όταν μια μετατροπή ανά σελίδα ολοκληρώνεται επιτυχώς. |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | Το γεγονός ενεργοποιείται μία φορά ανά σελίδα όταν μια μετατροπή ανά σελίδα αποτυγχάνει. |

### Δείτε επίσης
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
