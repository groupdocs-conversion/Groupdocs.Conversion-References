---
title: "Κλάση FontTransformation"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Περιγράφει τη διαμόρφωση μετασχηματισμού γραμματοσειράς, συμπεριλαμβανομένων των χαρακτηριστικών γραμματοσειράς, που εφαρμόζεται μετά τη φόρτωση του εγγράφου και την αντικατάσταση γραμματοσειράς."
type: docs
url: /el/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 200
---


## FontTransformation class

Περιγράφει τη διαμόρφωση μετασχηματισμού γραμματοσειράς, συμπεριλαμβανομένων των χαρακτηριστικών γραμματοσειράς, που εφαρμόζεται μετά τη φόρτωση του εγγράφου και την αντικατάσταση γραμματοσειράς.

Ο τύπος FontTransformation εκθέτει τα ακόλουθα μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | Δημιουργεί μια μετατροπή γραμματοσειράς με ακριβή αντιστοίχιση γραμματοσειράς (το μέγεθος και το στυλ πρέπει να ταιριάζουν). |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | Δημιουργεί μια μετατροπή γραμματοσειράς μόνο με το όνομα, ταιριάζοντας με οποιοδήποτε μέγεθος και στυλ, με τη γραμματοσειρά αντικατάστασης να διατηρεί το μέγεθος και το στυλ της αρχικής γραμματοσειράς. |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | Δημιουργεί μια μετατροπή γραμματοσειράς με ευέλικτες επιλογές αντιστοίχισης. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Καθορίζει εάν δύο παρουσίες αντικειμένων είναι ίσες. (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | Η ιδιότητα υποδεικνύει εάν ταιριάζει οποιοδήποτε μέγεθος γραμματοσειράς για το αρχικό όνομα γραμματοσειράς (true) ή μόνο το ακριβές μέγεθος γραμματοσειράς που καθορίζεται στο `OriginalFont` (false). |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | Η ιδιότητα καθορίζει εάν ταιριάζει οποιοδήποτε στυλ γραμματοσειράς (bold, italic, underline) της αρχικής γραμματοσειράς (True) ή απαιτείται το ακριβές στυλ γραμματοσειράς που καθορίζεται στο `OriginalFont` (False). |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | Η προδιαγραφή της αρχικής γραμματοσειράς για αντιστοίχιση και αντικατάσταση. |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | Η προδιαγραφή της γραμματοσειράς αντικατάστασης. |

### Δείτε επίσης
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
