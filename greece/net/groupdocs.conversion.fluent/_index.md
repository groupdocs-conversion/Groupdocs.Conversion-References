---
title: "GroupDocs.Conversion.Fluent"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ο χώρος ονομάτων παρέχει διεπαφές για ρευστή μετατροπή."
type: docs
weight: 60
url: /el/net/groupdocs.conversion.fluent/
---
Ο χώρος ονομάτων παρέχει διεπαφές για ρευστή μετατροπή.

## Διεπαφές

| Διεπαφή | Περιγραφή |
| --- | --- |
| [IConversionByPageCompleted](./iconversionbypagecompleted) | Η σελίδα μετατροπής ολοκληρώθηκε |
| [IConversionByPageCompletedOrConvert](./iconversionbypagecompletedorconvert) | Διαχειριστείτε την ολοκλήρωση της μετατροπής ή εκτελέστε τη μετατροπή |
| [IConversionByPageHandlerOnly](./iconversionbypagehandleronly) | Ευέλικτη διεπαφή για ορισμό μόνο χειριστών μετατροπής ανά σελίδα. Οι χειριστές καταχωρούνται μέσω [`IConversionByPageHandlersStage`](../groupdocs.conversion.fluent/iconversionbypagehandlersstage). |
| [IConversionByPageHandlersStage](./iconversionbypagehandlersstage) | Εξομαλυνμένο στάδιο χειριστών μετατροπής ανά σελίδα. Καθρεπτικό ανά σελίδα του [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionByPageOptionsOrHandlerSetup](./iconversionbypageoptionsorhandlersetup) | Ευέλικτη διεπαφή για ορισμό επιλογών μετατροπής ανά σελίδα ή ρύθμιση χειριστών. Επιτρέπει τον ορισμό επιλογών ή χειριστών με οποιαδήποτε σειρά, αλλά μόνο μία φορά για καθένα, ή την παράλειψη και των δύο. |
| [IConversionCompleted](./iconversioncompleted) | Διαχειριστείτε την ολοκλήρωση της μετατροπής |
| [IConversionCompletedOrConvert](./iconversioncompletedorconvert) | Διαχειριστείτε την ολοκλήρωση της μετατροπής ή εκτελέστε τη μετατροπή |
| [IConversionCompressResult](./iconversioncompressresult) | Μπορεί να συμπιέσει όλα τα αποτελέσματα της μετατροπής σε ένα ενιαίο αρχείο |
| [IConversionCompressResultCompletedOrConvert](./iconversioncompressresultcompletedorconvert) | Συνέχεια μετά το `Compress(...)`. Συνεχίστε με το `Convert`; καταχωρήστε τον χειριστή συμπιεσμένου ρεύματος στο αρχικό στάδιο μέσω [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents). |
| [IConversionConvert](./iconversionconvert) | Εκτελέστε τη μετατροπή |
| [IConversionConvertByPageOptions](./iconversionconvertbypageoptions) | Επιλογές μετατροπής |
| [IConversionConvertOptionOrCompletedOrConvert](./iconversionconvertoptionorcompletedorconvert) | Επιλογές μετατροπής ή ολοκλήρωση μετατροπής ή εκτέλεση |
| [IConversionConvertOptionOrPageCompletedOrConvert](./iconversionconvertoptionorpagecompletedorconvert) | Επιλογές μετατροπής ή ολοκλήρωση μετατροπής ή εκτέλεση |
| [IConversionConvertOptions](./iconversionconvertoptions) | Επιλογές μετατροπής |
| [IConversionConvertOrCompress](./iconversionconvertorcompress) | Συμπιέστε ή μετατρέψτε |
| [IConversionFrom](./iconversionfrom) | Ρυθμίστε την πηγή για τη μετατροπή |
| [IConversionGetDocumentInfo](./iconversiongetdocumentinfo) | Λαμβάνει πληροφορίες του πηγαίου εγγράφου - αριθμός σελίδων και άλλες ιδιότητες εγγράφου ειδικές για τον τύπο αρχείου. |
| [IConversionGetPossibleConversions](./iconversiongetpossibleconversions) | Λαμβάνει τις πιθανές μετατροπές για το πηγαίο έγγραφο. |
| [IConversionHandlerOnly](./iconversionhandleronly) | Ευέλικτη διεπαφή για ορισμό μόνο χειριστών μετατροπής. Οι χειριστές καταχωρούνται μέσω [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionHandlersStage](./iconversionhandlersstage) | Εξομαλυνμένο στάδιο χειριστών μετατροπής. Επιτρέπει τον ορισμό των `OnConversionCompleted` ή `OnConversionFailed` με οποιαδήποτε σειρά και οποιονδήποτε αριθμό φορών, πριν προχωρήσετε στο `Convert` / `Compress`. Τα συμβάντα πρέπει να καταχωρούνται στο αρχικό στάδιο μέσω [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents) αντί σε αυτό το στάδιο. |
| [IConversionIsPasswordProtected](./iconversionispasswordprotected) | Ελέγχει αν το πηγαίο έγγραφο είναι προστατευμένο με κωδικό |
| [IConversionLoadOptions](./iconversionloadoptions) | Επιλογές φόρτωσης μετατροπής |
| [IConversionLoadOptionsOrSourceDocumentLoaded](./iconversionloadoptionsorsourcedocumentloaded) | Επιλογές φόρτωσης μετατροπής ή ενέργειες με το φορτωμένο έγγραφο |
| [IConversionOptionsOnly](./iconversionoptionsonly) | Ευέλικτη διεπαφή για ορισμό μόνο επιλογών μετατροπής. |
| [IConversionOptionsOrHandlerSetup](./iconversionoptionsorhandlersetup) | Επιλογές μετατροπής ή ρύθμιση χειριστή μετατροπής. |
| [IConversionSettings](./iconversionsettings) | Ρυθμίστε τις ρυθμίσεις μετατροπής ή τα συμβάντα στο αρχικό στάδιο (πριν το `Load`). |
| [IConversionSettingsOrConversionFrom](./iconversionsettingsorconversionfrom) | Ρυθμίσεις μετατροπής ή πηγή μετατροπής |
| [IConversionSourceDocumentLoaded](./iconversionsourcedocumentloaded) | Παρέχει πιθανές ενέργειες με το φορτωμένο έγγραφο |
| [IConversionTo](./iconversionto) | Ορίστε πώς θα αποθηκευτεί το μετατρεπόμενο έγγραφο |

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
