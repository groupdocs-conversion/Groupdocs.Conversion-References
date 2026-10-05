---
title: "IConversionByPageHandlerOnly κλάση"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Παρέχει μια αβίαστη διεπαφή για τον ορισμό μόνο χειριστών μετατροπής ανά σελίδα."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

Παρέχει μια αβίαστη διεπαφή για τον ορισμό μόνο χειριστών μετατροπής ανά σελίδα.

Κληρονομεί το [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) για `Convert`/`Compress`; οι σταδικές υπερφορτώσεις `OnConversion*` διατηρούνται μέσω της λέξης-κλειδί `new` για τη διατήρηση της συμβατότητας προς τα πίσω.

Ο τύπος IConversionByPageHandlerOnly εκθέτει τα ακόλουθα μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | Συμπιέζει τα αποτελέσματα της μετατροπής· καταχωρίστε έναν χειριστή συμπιεσμένου‑ρεύματος στο αρχικό στάδιο μέσω του [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (ορίζοντας το `OnCompressionCompleted`) αντί να χρησιμοποιήσετε τη παρωχημένη μέθοδο ευέλικτης αλυσίδας. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | Εκτελεί την αλυσίδα μετατροπής. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή σελίδας ολοκληρωθεί επιτυχώς. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή σελίδας αποτύχει. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### Δείτε επίσης
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
