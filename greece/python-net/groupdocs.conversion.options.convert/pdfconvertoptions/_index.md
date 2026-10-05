---
title: "PdfConvertOptions κλάση"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Οι επιλογές για μετατροπή σε τύπο αρχείου PDF."
type: docs
url: /el/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/
is_root: false
weight: 340
---


## PdfConvertOptions class

Οι επιλογές για μετατροπή σε τύπο αρχείου PDF.

Ο τύπος PdfConvertOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/) | Δημιουργεί ένα νέο αντικείμενο [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/). |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/dpi/) | Το επιθυμητό DPI σελίδας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι 96 dpi. |
| [embed_full_fonts](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/) | Η ιδιότητα καθορίζει αν το πλήρες αρχείο γραμματοσειράς ενσωματώνεται στο PDF αντί για ένα υποσύνολο. |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/fallback_page_size/) | Το εφεδρικό μέγεθος σελίδας. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/format/) | Ο επιθυμητός τύπος αρχείου στο οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/margin_settings/) | Οι ρυθμίσεις περιθωρίων που εφαρμόζονται κατά τη μετατροπή PDF. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/orientation_settings/) | Οι ρυθμίσεις προσανατολισμού. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/page_number/) | Ο αριθμός σελίδας από την οποία ξεκινά η μετατροπή. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages/) | Η λίστα των δεικτών σελίδων που θα μετατραπούν· καθορίστε για να μετατρέψετε συγκεκριμένες σελίδες. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages_count/) | Ο αριθμός των σελίδων που θα μετατραπούν ξεκινώντας από το `page_number`. |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/password/) | Ο κωδικός πρόσβασης που χρησιμοποιείται για την προστασία του μετατρεπόμενου εγγράφου. |
| [pdf_options](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pdf_options/) | Οι ειδικές επιλογές μετατροπής PDF. |
| [resize_mode](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/resize_mode/) | Η λειτουργία αλλαγής μεγέθους καθορίζει πώς πρέπει να κλιμακωθεί το περιεχόμενο όταν αλλάζει το μέγεθος της σελίδας. Η προεπιλογή είναι AlignTopLeft (χωρίς κλιμάκωση). |
| [rotate](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/rotate/) | Η περιστροφή σελίδας. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/size_settings/) | Οι ρυθμίσεις μεγέθους σελίδας που χρησιμοποιούνται κατά τη μετατροπή PDF. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/watermark/) | Οι συγκεκριμένες επιλογές του υδατογραφήματος. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν το `PdfConvertOptions`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### Δείτε επίσης
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
