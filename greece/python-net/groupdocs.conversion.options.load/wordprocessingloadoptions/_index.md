---
title: "Κλάση WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Παρέχει επιλογές για τη φόρτωση εγγράφων WordProcessing."
type: docs
url: /el/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/
is_root: false
weight: 580
---


## WordProcessingLoadOptions class

Παρέχει επιλογές για τη φόρτωση εγγράφων WordProcessing.

Διαδικασία Επεξεργασίας Γραμματοσειράς:

Φάση 1 - Αντικατάσταση γραμματοσειράς (κατά τη φόρτωση του εγγράφου):
- Handles missing/unavailable fonts using FontSubstitutes, DefaultFont, and system substitution
- Processing order: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

Φάση 2 - Αντικατάσταση γραμματοσειράς (μετά τη φόρτωση του εγγράφου):
- Modifies any existing fonts in the loaded document using FontReplacements
- Applied after all font substitution is complete

Ο τύπος WordProcessingLoadOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/__init__/) | Αρχικοποιεί μια νέα παρουσία του [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/). |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Καθορίζει εάν δύο παρουσίες αντικειμένων είναι ίσες. (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [auto_detect_rtl_direction](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/) | Η ιδιότητα auto_detect_rtl_direction καθορίζει εάν οι παράγραφοι και τα τμήματα κειμένου με κυρίως δεξιόστροφη (right-to-left) γραφή έχουν τις σημαίες bidi διορθωμένες πριν από τη μετατροπή. |
| [bookmark_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/bookmark_options/) | Οι επιλογές σελιδοδεικτών. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_built_in_document_properties/) | Η σημαία που υποδεικνύει εάν οι ενσωματωμένες ιδιότητες εγγράφου διαγράφονται κατά τη φόρτωση ενός εγγράφου Word processing. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_custom_document_properties/) | Η ιδιότητα ClearCustomDocumentProperties. |
| [comment_display_mode](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/comment_display_mode/) | Η λειτουργία εμφάνισης σχολίων καθορίζει πώς θα εμφανίζονται τα σχόλια στο τελικό έγγραφο. Η προεπιλογή είναι `ShowInBalloons`. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owned/) | Η ιδιότητα υλοποιεί το [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/). Η προεπιλογή είναι False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owner/) | Η σημαία convert_owner υποδεικνύει εάν θα μετατραπεί ο ιδιοκτήτης του εγγράφου. Η προεπιλογή είναι True. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/) | Η προεπιλεγμένη γραμματοσειρά για ένα έγγραφο WordProcessing. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/depth/) | Το βάθος των επιλογών φόρτωσης του περιέκτη εγγράφου. Η προεπιλογή είναι 1. |
| [embed_true_type_fonts](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/embed_true_type_fonts/) | Η ιδιότητα embed_true_type_fonts καθορίζει εάν οι γραμματοσειρές TrueType ενσωματώνονται στο τελικό έγγραφο. Η προεπιλογή είναι True. |
| [font_config_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/) | Η ιδιότητα ενεργοποιεί την αυτόματη αντικατάσταση των ελλιπών γραμματοσειρών βάσει του συστημικού FontConfig. Η προεπιλογή είναι False. |
| [font_info_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/) | Η σημαία που ενεργοποιεί την αυτόματη αντικατάσταση των ελλιπών γραμματοσειρών βάσει του FontInfo στο έγγραφο. Προεπιλογή: False. |
| [font_name_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/) | Η ιδιότητα υποδεικνύει εάν οι ελλιπείς γραμματοσειρές αντικαθίστανται αυτόματα βάσει του ονόματος γραμματοσειράς. Προεπιλογή: False. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/) | Οι υποκατάστατες γραμματοσειρές που χρησιμοποιούνται κατά τη μετατροπή ενός εγγράφου WordProcessing. |
| [font_transformations](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_transformations/) | Οι μετασχηματισμοί γραμματοσειρών που εφαρμόζονται μετά την ολοκλήρωση της φόρτωσης του εγγράφου και της αντικατάστασης γραμματοσειρών, επιτρέπουν την τροποποίηση οποιωνδήποτε γραμματοσειρών στο έγγραφο, συμπεριλαμβανομένων των επιτυχώς φορτωμένων. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/format/) | Ο τύπος αρχείου του εισερχόμενου εγγράφου. |
| [hide_word_tracked_changes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_word_tracked_changes/) | Η ιδιότητα hide_word_tracked_changes κρύβει τις σημειώσεις και τις αλλαγές παρακολούθησης για έγγραφα Word. |
| [hyphenation_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenation_options/) | Οι επιλογές συλλαβισμού για έγγραφα WordProcessing. |
| [keep_date_field_original_value](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/keep_date_field_original_value/) | Η ιδιότητα keep_date_field_original_value καθορίζει εάν διατηρείται η αρχική τιμή ενός πεδίου ημερομηνίας. Η προεπιλογή είναι False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/margin_settings/) | Οι ρυθμίσεις περιθωρίων. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/page_numbering/) | Η σημαία δημιουργίας αρίθμησης σελίδων για το μετατρεπόμενο έγγραφο (προεπιλογή: False). |
| [password](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/password/) | Ο κωδικός πρόσβασης για την αφαίρεση προστασίας ενός προστατευμένου εγγράφου. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_document_structure/) | Η σημαία που υποδεικνύει εάν η δομή του εγγράφου πρέπει να διατηρηθεί κατά τη μετατροπή σε PDF (η προεπιλογή είναι False). |
| [preserve_form_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_form_fields/) | Η ιδιότητα υποδεικνύει εάν τα πεδία φόρμας του Microsoft Word διατηρούνται ως πεδία φόρμας στο παραγόμενο PDF ή μετατρέπονται σε κείμενο. Η προεπιλογή είναι False. |
| [show_full_commenter_name](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/show_full_commenter_name/) | Το πλήρες όνομα του σχολιαστή εμφανίζεται στα σχόλια όταν οριστεί σε True. Η προεπιλογή είναι False. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/size_settings/) | Οι ρυθμίσεις μεγέθους για το έγγραφο WordProcessing ([`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/)). |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/skip_external_resources/) | Η σημαία που καθορίζει εάν οι εξωτερικοί πόροι παραλείπονται κατά τη φόρτωση ενός εγγράφου. |
| [update_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_fields/) | Η επιλογή για ενημέρωση των πεδίων μετά τη φόρτωση. Προεπιλογή: False. |
| [update_page_layout](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_page_layout/) | Η διάταξη σελίδας ενημερώνεται μετά τη φόρτωση. Προεπιλογή: False. |
| [use_text_shaper](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/use_text_shaper/) | Η ιδιότητα υποδεικνύει εάν θα χρησιμοποιηθεί ένας διαμορφωτής κειμένου για καλύτερη εμφάνιση του kerning. Η προεπιλογή είναι False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/whitelisted_resources/) | Οι επιτρεπόμενοι πόροι για τη φόρτωση εξωτερικού περιεχομένου, υλοποιώντας το [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Παράδειγμα

```python
from groupdocs.conversion.options.load import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
load_options.password = "secret"
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν το `WordProcessingLoadOptions`:

* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### Δείτε επίσης
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
