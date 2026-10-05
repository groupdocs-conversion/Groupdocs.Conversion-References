---
title: "DatabaseFileType κλάση"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Ορίζει έγγραφα βάσης δεδομένων."
type: docs
url: /el/python-net/groupdocs.conversion.filetypes/databasefiletype/
is_root: false
weight: 40
---


## DatabaseFileType class

Ορίζει έγγραφα βάσης δεδομένων. Περιλαμβάνει τους ακόλουθους τύπους αρχείων.

- [`DatabaseFileType.nsf`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/nsf/)
- [`DatabaseFileType.log`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/log/)
- [`DatabaseFileType.sql`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/sql/)

Ο τύπος DatabaseFileType εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/__init__/) | Αρχικοποιεί ένα νέο DatabaseFileType για σειριοποίηση. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Συγκρίνει το τρέχον αντικείμενο με άλλο. (κληρονομείται από το [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (κληρονομείται από το [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Υλοποιεί τη σύγκριση ισότητας που ορίζεται από το [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (κληρονομείται από το [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (κληρονομείται από [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (κληρονομείται από το [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (κληρονομείται από το [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Λαμβάνει το FileType για την παρεχόμενη επέκταση αρχείου. (κληρονομείται από [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Επιστρέφει το FileType για το συγκεκριμένο file_name. (κληρονομείται από [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Επιστρέφει το FileType για το παρεχόμενο ρεύμα εγγράφου. (κληρονομείται από [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (κληρονομείται από το [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (κληρονομείται από [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Παρέχει τη προεπιλεγμένη συνάρτηση hash. (κληρονομείται από το [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Αναπαράσταση συμβολοσειράς του τύπου αρχείου. (κληρονομείται από [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | Η περιγραφή του τύπου αρχείου. (κληρονομείται από [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | Η επέκταση αρχείου. (κληρονομείται από [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | Η οικογένεια αρχείων. (κληρονομείται από [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Η μορφή αρχείου. (κληρονομείται από [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [NSF](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/nsf/) | Ένα αρχείο με επέκταση .nsf (Notes Storage Facility) είναι μια μορφή αρχείου βάσης δεδομένων που χρησιμοποιείται από το λογισμικό IBM Notes, το οποίο προηγουμένως ήταν γνωστό ως Lotus Notes. Καθορίζει το σχήμα για την αποθήκευση διαφορετικών τύπων αντικειμένων όπως email, ραντεβού, έγγραφα, φόρμες και προβολές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [LOG](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/log/) | Ένα αρχείο με επέκταση .log περιέχει λίστα απλού κειμένου με χρονική σήμανση. Συνήθως, ορισμένες λεπτομέρειες δραστηριότητας καταγράφονται από το λογισμικό ή τα λειτουργικά συστήματα για να βοηθήσουν τους προγραμματιστές ή τους χρήστες να παρακολουθήσουν τι συνέβαινε σε μια συγκεκριμένη χρονική περίοδο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [SQL](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/sql/) | Ένα αρχείο με επέκταση .sql είναι ένα αρχείο Structured Query Language (SQL) που περιέχει κώδικα για εργασία με σχεσιακές βάσεις δεδομένων. Χρησιμοποιείται για τη σύνταξη δηλώσεων SQL για λειτουργίες CRUD (Create, Read, Update, Delete) σε βάσεις δεδομένων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Άγνωστος τύπος αρχείου (κληρονομείται από [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Δείτε επίσης
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
