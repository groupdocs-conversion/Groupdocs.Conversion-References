---
title: "groupdocs.conversion.fluent"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Τύποι κάτω από groupdocs.conversion.fluent."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/
is_root: false
weight: 50
---


Τύποι κάτω από `groupdocs.conversion.fluent`.

### Κλάσεις
| Κλάση | Περιγραφή |
| :- | :- |
| [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/) | Διαχειρίζεται την ολοκλήρωση της σελίδας μετατροπής. |
| [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/) | Διαχειρίζεται την ολοκλήρωση της μετατροπής ή εκτελεί τη μετατροπή. |
| [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/) | Παρέχει μια αβίαστη διεπαφή μετά τον ορισμό του `OnConversionFailed` για τη μετατροπή σελίδας. Επιτρέπει τον ορισμό του `OnConversionCompleted` ή τη συνέχιση με `Convert`/`Compress`. |
| [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/) | Αναπαριστά τη αβίαστη διεπαφή μετά τον ορισμό του `OnConversionCompleted` για τη μετατροπή σελίδας, επιτρέποντας τη διαμόρφωση του `OnConversionFailed` ή τη συνέχιση με `Convert`/`Compress`. |
| [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/) | Παρέχει μια αβίαστη διεπαφή για τον ορισμό μόνο χειριστών μετατροπής ανά σελίδα. |
| [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/) | Παρέχει μια αβίαστη διεπαφή για τον ορισμό χειριστών μετατροπής σελίδας. |
| [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) | Αναπαριστά ένα εξομαλυνμένο στάδιο χειριστών μετατροπής ανά σελίδα. |
| [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/) | Η αβίαστη διεπαφή για τον ορισμό επιλογών μετατροπής ανά σελίδα ή τη ρύθμιση του χειριστή. |
| [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/) | Διαχειρίζεται την ολοκλήρωση της μετατροπής. |
| [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/) | Διαχειριστεί την ολοκλήρωση της μετατροπής ή εκτελέστε τη μετατροπή. |
| [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/) | Συμπιέζει όλα τα αποτελέσματα της μετατροπής σε ένα ενιαίο αρχείο. |
| [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/) | Διαχειρίζεται την ολοκλήρωση της συμπίεσης. |
| [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/) | Συνέχεια μετά το `Compress(...)`. Προχωρήστε απευθείας με `Convert`; η κληρονομημένη [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) είναι παρωχημένη — καταχωρήστε τον χειριστή στο αρχικό στάδιο μέσω του [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) αντί αυτού. |
| [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/) | Εκτελέστε τη μετατροπή. |
| [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/) | Αναπαριστά τις επιλογές μετατροπής. |
| [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/) | Αναπαριστά τις επιλογές μετατροπής, τη διαχείριση ολοκλήρωσης ή την εκτέλεση μιας μετατροπής. |
| [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/) | Αναπαριστά τις επιλογές μετατροπής, τη διαχείριση ολοκλήρωσης ή την εκτέλεση. |
| [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/) | Αναπαριστά τις επιλογές μετατροπής. |
| [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/) | Συμπιέστε ή μετατρέψτε. |
| [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/) | Ρυθμίζει την πηγή για τη μετατροπή. |
| [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/) | Ανακτά πληροφορίες του πηγαίου εγγράφου, συμπεριλαμβανομένου του αριθμού σελίδων και άλλων ιδιοτήτων ειδικών για τον τύπο αρχείου. |
| [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/) | Λαμβάνει τις πιθανές μετατροπές για το πηγαίο έγγραφο. |
| [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/) | Αναπαριστά τη αβίαστη διεπαφή μετά τον ορισμό του `OnConversionFailed`, επιτρέποντας τον ορισμό του `OnConversionCompleted` ή τη συνέχιση με `Convert`/`Compress`. |
| [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/) | Παρέχει μια αβίαστη διεπαφή μετά τον ορισμό του `OnConversionCompleted`, επιτρέποντας τη διαμόρφωση του `OnConversionFailed` ή τη συνέχιση με `Convert`/`Compress`. |
| [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/) | Παρέχει μια αβίαστη διεπαφή για τον ορισμό μόνο χειριστών μετατροπής. |
| [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/) | Παρέχει μια αβίαστη διεπαφή για τον ορισμό χειριστών μετατροπής. Επιτρέπει τον ορισμό του `OnConversionCompleted` και/ή του `OnConversionFailed` με οποιαδήποτε σειρά, το πολύ μία φορά ο καθένας, ή την παράλειψη και των δύο. |
| [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/) | Αναπαριστά ένα εξομαλυνμένο στάδιο χειριστών μετατροπής. |
| [`IConversionIsPasswordProtected`](/conversion/python-net/groupdocs.conversion.fluent/iconversionispasswordprotected/) | Ελέγχει εάν το πηγαίο έγγραφο είναι προστατευμένο με κωδικό. |
| [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/) | Αντιπροσωπεύει τις επιλογές φόρτωσης μετατροπής. |
| [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/) | Αντιπροσωπεύει τις επιλογές φόρτωσης μετατροπής ή ενέργειες με ένα φορτωμένο έγγραφο. |
| [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/) | Παρέχει μια ρευστή διεπαφή για τον καθορισμό μόνο των επιλογών μετατροπής. |
| [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/) | Αντιπροσωπεύει τις επιλογές μετατροπής ή τη ρύθμιση του χειριστή μετατροπής. |
| [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/) | Ρυθμίστε τις ρυθμίσεις μετατροπής ή τα γεγονότα στο στάδιο εισόδου (πριν το `Load`). |
| [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/) | Αντιπροσωπεύει τις ρυθμίσεις μετατροπής ή την πηγή μετατροπής. |
| [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/) | Παρέχει πιθανές ενέργειες με το φορτωμένο έγγραφο. |
| [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/) | Ορίζει πώς αποθηκεύεται το μετατρεπόμενο έγγραφο. |
