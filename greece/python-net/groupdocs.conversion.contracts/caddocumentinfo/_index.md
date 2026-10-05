---
title: "CadDocumentInfo κλάση"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Περιέχει μεταδεδομένα εγγράφου Cad."
type: docs
url: /el/python-net/groupdocs.conversion.contracts/caddocumentinfo/
is_root: false
weight: 50
---


## CadDocumentInfo class

Περιέχει μεταδεδομένα εγγράφου Cad.

[`DocumentInfo.pages_count`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) counts the sheets the drawing offers under the load options it was read with.

Χωρίς την ρητή καθορισμένη τιμή του [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) τα φύλλα είναι ο χώρος μοντέλου, ο οποίος είναι πάντα δυνατόν για εκτύπωση και επομένως πάντα ένα φύλλο, συν κάθε διάταξη paper-space της οποίας η αποθηκευμένη ρύθμιση σελίδας έχει θετικό πλάτος και ύψος, περιορισμένη από το [`CadLoadOptions.layout_scope`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/). Οι ρητές ονομασίες διάταξης κερδίζουν άμεσα: τα φύλλα είναι τότε τα παρεχόμενα ονόματα που περιέχει το σχέδιο, ταιριασμένα κατά σειρά, χωρίς να τα φιλτράρει ούτε το scope ούτε η ρύθμιση σελίδας.

Για ένα DWF το δημοσιευμένο σύνολο σελίδων αναφέρεται. Η καταμέτρηση ενός κάτω από ένα είναι μηδέν, που αναφέρεται όταν το ζητούμενο scope δεν ταιριάζει με κανένα φύλλο ενός σχεδίου που το προσφέρει: τα μεταδεδομένα εξακολουθούν να περιγράφουν το σχέδιο, και το μηδέν σημαίνει ότι το scope δεν επιλέγει τίποτα αντί να αποτύχει ο καλών που ρώτησε τι περιέχει το σχέδιο. Μια μετατροπή υπό τις ίδιες επιλογές φόρτωσης αποτυγχάνει.

Η καταμέτρηση επομένως δεν είναι το μέγεθος του [`CadDocumentInfo.layouts`](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/), το οποίο παραθέτει κάθε ρύθμιση εκτύπωσης που περιέχει το σχέδιο, συμπεριλαμβανομένων αυτών από τα οποία δεν μπορεί να δημοσιευθεί φύλλο, και δεν προβλέπει πόσες σελίδες θα εκδώσει μια συγκεκριμένη μετατροπή.

Ο τύπος CadDocumentInfo εκθέτει τα ακόλουθα μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_string/) |  |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/creation_date/) | Η ημερομηνία δημιουργίας του εγγράφου. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/format/) | Η μορφή του εγγράφου. |
| [height](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/height/) | Το ύψος του εγγράφου CAD. |
| [layers](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layers/) | Οι στρώσεις στο έγγραφο. |
| [layouts](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) | Οι διατάξεις στο έγγραφο. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/pages_count/) | Ο αριθμός σελίδων του εγγράφου. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/property_names/) | Η απαρίθμηση όλων των ιδιοτήτων που μπορούν να ανακτηθούν για τις τρέχουσες πληροφορίες εγγράφου. |
| [size](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/size/) | Το μέγεθος του εγγράφου σε bytes. |
| [width](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/width/) | Το πλάτος του εγγράφου CAD. |

### Δείτε επίσης
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
