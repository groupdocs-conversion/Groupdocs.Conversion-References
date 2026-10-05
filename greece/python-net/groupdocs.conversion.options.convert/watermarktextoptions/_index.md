---
title: "WatermarkTextOptions κλάση"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Επιλογές για ορισμό κειμενικού υδατογραφήματος στο μετατρεπόμενο έγγραφο."
type: docs
url: /el/python-net/groupdocs.conversion.options.convert/watermarktextoptions/
is_root: false
weight: 590
---


## WatermarkTextOptions class

Επιλογές για ορισμό κειμενικού υδατογραφήματος στο μετατρεπόμενο έγγραφο.

Αντιπροσωπεύει τη διαμόρφωση της εμφάνισης του υδατογραφήματος. Μπορούν να διαμορφωθούν οι ακόλουθες ιδιότητες:

- `text`: The text to be used for the watermark.
- `font`: The font name used for the watermark text.
- `color`: The color of the watermark text.
- `top`: The top offset of the watermark.
- `left`: The left offset of the watermark.
- `width`: The width of the watermark.
- `height`: The height of the watermark.
- `background`: Whether the watermark is rendered in the background.

Ο τύπος WatermarkTextOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/__init__/#text) | Δημιουργεί ένα στιγμιότυπο WatermarkTextOptions με το καθορισμένο κείμενο υδατογραφήματος. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/clone/) | Κλωνοποιεί το τρέχον αντίγραφο. (κληρονομείται από [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Καθορίζει εάν δύο παρουσίες αντικειμένων είναι ίσες. (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. (κληρονομείται από το [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [color](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/color/) | Το χρώμα γραμματοσειράς του υδατογραφήματος εάν εφαρμοστεί κειμενικό υδατογράφημα. |
| [text](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/text/) | Το κείμενο του υδατογραφήματος. |
| [watermark_font](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/watermark_font/) | Η γραμματοσειρά του υδατογραφήματος που χρησιμοποιείται όταν εφαρμόζεται κειμενικό υδατογράφημα. |
| [auto_align](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/auto_align/) | Το υδατογράφημα κλιμακώνεται αυτόματα ώστε να ταιριάζει στο μέγεθος της σελίδας όταν οριστεί σε True. (κληρονομείται από [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [background](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/background/) | Το υδατογράφημα τοποθετείται ως φόντο· εάν είναι True, τοποθετείται στο κάτω μέρος, διαφορετικά τοποθετείται στην κορυφή (η προεπιλογή είναι False). (κληρονομείται από [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/height/) | Το ύψος του υδατογραφήματος. (κληρονομείται από [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [left](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/left/) | Η αριστερή θέση του υδατογραφήματος. (κληρονομείται από [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [rotation_angle](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/rotation_angle/) | Η γωνία περιστροφής του υδατογραφήματος. (κληρονομείται από [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [top](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/top/) | Η άνω θέση του υδατογραφήματος. (κληρονομείται από [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [transparency](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/transparency/) | Η διαφάνεια του υδατογραφήματος. Τιμή μεταξύ 0 και 1. Η τιμή 0 είναι πλήρως ορατή, η τιμή 1 είναι αόρατη. (κληρονομείται από [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/width/) | Το πλάτος του υδατογραφήματος. (κληρονομείται από [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |

### Παράδειγμα

```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

with Converter("./professional-services.docx") as converter:
    watermark = WatermarkTextOptions("DRAFT")
    watermark.color = Color.from_argb(128, 211, 211, 211)  # lite gray
    watermark.top = 10
    watermark.left = 10
    watermark.width = 300
    watermark.height = 300
    watermark.background = True

    options = PdfConvertOptions()
    options.pages_count = 1
    options.watermark = watermark

    converter.convert("./professional-services.pdf", options)
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `WatermarkTextOptions`:

* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)

### Δείτε επίσης
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
