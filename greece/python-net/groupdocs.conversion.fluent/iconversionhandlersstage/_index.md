---
title: "IConversionHandlersStage κλάση"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά ένα εξομαλυνμένο στάδιο χειριστών μετατροπής."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

Αναπαριστά ένα εξομαλυνμένο στάδιο χειριστών μετατροπής.

Επιτρέπει τον ορισμό του `OnConversionCompleted` ή του `OnConversionFailed` με οποιαδήποτε σειρά και οποιονδήποτε αριθμό φορών, πριν προχωρήσετε σε `Convert` / `Compress`. Τα γεγονότα πρέπει να καταχωρούνται στο αρχικό στάδιο μέσω του [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) αντί σε αυτό το στάδιο.

Ο τύπος IConversionHandlersStage εκθέτει τα ακόλουθα μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | Συμπιέζει τα αποτελέσματα της μετατροπής. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | Εκτελεί την αλυσίδα μετατροπής. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | Καταχωρεί μια κλήση επιστροφής που θα εκτελείται όταν μια μετατροπή εγγράφου ολοκληρωθεί επιτυχώς, αντικαθιστώντας οποιονδήποτε προηγουμένως ορισμένο χειριστή κατά την επανεκτέλεση. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή εγγράφου αποτύχει. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### Δείτε επίσης
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
