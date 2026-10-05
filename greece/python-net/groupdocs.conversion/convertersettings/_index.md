---
title: "Κλάση ConverterSettings"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Ορίζει τις ρυθμίσεις για την προσαρμογή της συμπεριφοράς του Converter."
type: docs
url: /el/python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

Ορίζει τις ρυθμίσεις για την προσαρμογή της συμπεριφοράς του Converter.

Ο τύπος ConverterSettings εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | Αρχικοποιεί μια νέα παρουσία του ConverterSettings με προεπιλεγμένες τιμές. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | Η υλοποίηση της κρυφής μνήμης που χρησιμοποιείται για την αποθήκευση των αποτελεσμάτων μετατροπής. |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | Οι διαδρομές των προσαρμοσμένων καταλόγων γραμματοσειρών. |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | Η υλοποίηση του ακροατή μετατροπέα που χρησιμοποιείται για την παρακολούθηση της κατάστασης και της προόδου της μετατροπής, με τις κλήσεις Started, Progress και Completed να προωθούνται στο [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), και [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) κατά τη δημιουργία του [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | Η υλοποίηση του καταγραφέα που χρησιμοποιείται για την καταγραφή της διαδικασίας μετατροπής. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | Ο χειριστής συμβάντος για την ολοκλήρωση της συμπίεσης. |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | Ο χειριστής συμβάντος που καλείται όταν η μετατροπή ανά σελίδα αποτυγχάνει. |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | Ο χειριστής συμβάντος που καλείται όταν μια μετατροπή αποτυγχάνει. |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | Ο μετατροπέας σαρώει τους καταλόγους γραμματοσειρών αναδρομικά όταν ορίζεται σε True. |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | Ο φάκελος προσωρινής αποθήκευσης που χρησιμοποιείται για τη μετατροπή. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Δείτε επίσης
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
