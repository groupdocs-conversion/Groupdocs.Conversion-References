---
title: "WordProcessingConvertOptions κλάση"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Οι επιλογές για μετατροπή σε τύπο αρχείου Επεξεργασίας Κειμένου."
type: docs
url: /el/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
is_root: false
weight: 620
---


## WordProcessingConvertOptions class

Οι επιλογές για μετατροπή σε τύπο αρχείου Επεξεργασίας Κειμένου.

Ο τύπος WordProcessingConvertOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/__init__/) | Αρχικοποιεί ένα νέο στιγμιότυπο του [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/). |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi/) | Το επιθυμητό DPI σελίδας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι 96 dpi. |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallback_page_size/) | Το εφεδρικό μέγεθος σελίδας. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/format/) | Ο επιθυμητός τύπος αρχείου στο οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/margin_settings/) | Οι ρυθμίσεις περιθωρίων για τη μετατροπή, που αντιπροσωπεύονται από [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/). |
| [markdown_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdown_options/) | Οι επιλογές μετατροπής Markdown. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/orientation_settings/) | Οι ρυθμίσεις προσανατολισμού. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/page_number/) | Ο αριθμός σελίδας από την οποία ξεκινά η μετατροπή. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages/) | Η λίστα των δεικτών σελίδων που θα μετατραπούν. Πρέπει να καθοριστεί για μετατροπή συγκεκριμένων σελίδων. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages_count/) | Ο αριθμός των σελίδων που θα μετατραπούν ξεκινώντας από το `PageNumber`. |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/password/) | Ο κωδικός πρόσβασης που χρησιμοποιείται για την προστασία του μετατρεπόμενου εγγράφου. |
| [pdf_recognition_mode](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdf_recognition_mode/) | Η λειτουργία αναγνώρισης PDF που χρησιμοποιείται για τη μετατροπή, υλοποιώντας το [`IPdfRecognitionModeOptions.pdf_recognition_mode`](/conversion/python-net/groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions/pdf_recognition_mode/). |
| [rtf_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtf_options/) | Οι συγκεκριμένες επιλογές μετατροπής RTF. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/size_settings/) | Οι ρυθμίσεις μεγέθους για τη μετατροπή. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/watermark/) | Οι συγκεκριμένες επιλογές του υδατογραφήματος. |
| [zoom](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom/) | Το επίπεδο ζουμ σε ποσοστό. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

with Converter("./business-plan.docx") as converter:
    options = WordProcessingConvertOptions()
    options.format = WordProcessingFileType.TXT
    converter.convert("./business-plan.txt", options)
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν το `WordProcessingConvertOptions`:

* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)

### Δείτε επίσης
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
