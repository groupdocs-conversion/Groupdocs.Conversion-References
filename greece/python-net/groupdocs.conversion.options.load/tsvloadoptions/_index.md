---
title: "Κλάση TsvLoadOptions"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει τις επιλογές για τη φόρτωση εγγράφων TSV."
type: docs
url: /el/python-net/groupdocs.conversion.options.load/tsvloadoptions/
is_root: false
weight: 480
---


## TsvLoadOptions class

Αντιπροσωπεύει τις επιλογές για τη φόρτωση εγγράφων TSV.

Ο τύπος TsvLoadOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/__init__/) | Αρχικοποιεί ένα νέο στιγμιότυπο του [`TsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/). |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | Κλωνοποιεί το τρέχον στιγμιότυπο. (κληρονομείται από το [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Καθορίζει εάν δύο παρουσίες αντικειμένων είναι ίσες. (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/clear_built_in_document_properties/) | Η ιδιότητα αφαιρεί τις ενσωματωμένες ιδιότητες μεταδεδομένων από το έγγραφο. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/clear_custom_document_properties/) | Η ιδιότητα που αφαιρεί τις προσαρμοσμένες ιδιότητες μεταδεδομένων από το έγγραφο. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/convert_owned/) | Η επιλογή ελέγχει αν τα ιδιόκτητα έγγραφα στο δοχείο εγγράφων πρέπει να μετατραπούν. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/convert_owner/) | Η επιλογή ελέγχει αν το ίδιο το δοχείο του εγγράφου πρέπει να μετατραπεί· εάν είναι αληθές, το δοχείο θα είναι το πρώτο μετατρεπόμενο έγγραφο. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/default_font/) | Η γραμματοσειρά που θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/depth/) | Η επιλογή ελέγχει πόσα επίπεδα σε βάθος θα εκτελεστεί η μετατροπή. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/font_substitutes/) | Οι υποκαταστάσεις γραμματοσειρών. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/format/) | Ο τύπος αρχείου του εισερχόμενου εγγράφου. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/margin_settings/) | Οι ρυθμίσεις περιθωρίων σελίδας. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/size_settings/) | Οι ρυθμίσεις μεγέθους σελίδας. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/skip_external_resources/) | Η ιδιότητα καθορίζει εάν φορτώνονται εξωτερικοί πόροι· εάν είναι True, όλοι οι εξωτερικοί πόροι δεν θα φορτωθούν εκτός από εκείνους που βρίσκονται στη λίστα [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/) . Προεπιλογή: True. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/whitelisted_resources/) | Οι εξωτερικοί πόροι που θα φορτώνονται πάντα. |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | Η ιδιότητα καθορίζει εάν όλο το περιεχόμενο των στηλών ενός φύλλου αποδίδεται σε μία σελίδα στο αποτέλεσμα. (κληρονομείται από το [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | Οι γραμμές προσαρμόζονται αυτόματα κατά τη μετατροπή. (κληρονομείται από το [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | Η ιδιότητα καθορίζει εάν ελέγχονται οι περιορισμοί αρχείων Excel κατά την τροποποίηση αντικειμένων σχετικών με κελιά. (κληρονομείται από το [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | Ο αριθμός στηλών ανά σελίδα που χρησιμοποιείται για το διαχωρισμό ενός φύλλου εργασίας σε σελίδες· η προεπιλογή είναι 0, η οποία απενεργοποιεί την σελιδοποίηση. (κληρονομείται από το [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | Η περιοχή που θα μετατραπεί κατά τη μετατροπή σε μορφή μη‑φύλλου, π.χ. "D1:F8". (κληρονομείται από το [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | Η πληροφορία πολιτισμού του συστήματος που χρησιμοποιείται όταν φορτώνεται το αρχείο. (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | Η ιδιότητα υποδεικνύει εάν θα αγνοηθούν τα σφάλματα υπολογισμού τύπων. Το σφάλμα μπορεί να είναι μη υποστηριζόμενη λειτουργία, εξωτερικοί σύνδεσμοι κ.λπ. Η προεπιλογή είναι False. (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | Η ιδιότητα υποδεικνύει εάν το περιεχόμενο κάθε φύλλου μετατρέπεται σε μία σελίδα στο έγγραφο PDF. Η προεπιλεγμένη τιμή είναι True. (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | Η μετατροπή βελτιστοποιείται για μικρότερο μέγεθος αρχείου αντί για ποιότητα εκτύπωσης όταν οριστεί σε True κατά τη μετατροπή σε PDF. (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | Ο κωδικός πρόσβασης που χρησιμοποιείται για την αποπροστασία ενός προστατευμένου εγγράφου. (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | Η σημαία που υποδεικνύει εάν η δομή του εγγράφου πρέπει να διατηρηθεί κατά τη μετατροπή σε PDF (προεπιλογή είναι False). (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | Ο τρόπος με τον οποίο εκτυπώνονται τα σχόλια με το φύλλο. Η προεπιλογή είναι PrintNoComments. (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | Οι φάκελοι γραμματοσειρών επαναφέρονται πριν από τη φόρτωση του εγγράφου. (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | Ο αριθμός των γραμμών ανά σελίδα που χρησιμοποιείται για το διαχωρισμό ενός φύλλου εργασίας σε σελίδες, με προεπιλογή το 0 που σημαίνει χωρίς σελιδοποίηση. (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | Η λίστα των δεικτών φύλλων προς μετατροπή. (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | Το όνομα του φύλλου προς μετατροπή. (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | Η επιλογή εμφάνισης γραμμών πλέγματος κατά τη μετατροπή αρχείων Excel. (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | Η επιλογή εμφάνισης κρυφών φύλλων κατά τη μετατροπή αρχείων Excel. (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | Η ρύθμιση που παραλείπει κενές γραμμές και στήλες κατά τη μετατροπή. (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | Η ιδιότητα καθορίζει εάν τα υποσέλιδα παραλείπονται κατά τη μετατροπή εγγράφων λογιστικού φύλλου. Προεπιλογή: False. (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | Η επιλογή παράλειψης κεφαλίδων κατά τη μετατροπή εγγράφων λογιστικού φύλλου. Προεπιλογή: False. (κληρονομείται από [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |

### Δείτε επίσης
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
