---
title: "PdfConvertOptions-klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Alternativen för konvertering till PDF-filtyp."
type: docs
url: /sv/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/
is_root: false
weight: 340
---


## PdfConvertOptions class

Alternativen för konvertering till PDF-filtyp.

PdfConvertOptions-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/) | Initierar en ny [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) instans. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/dpi/) | Den önskade sidans DPI efter konvertering. Standardupplösningen är 96 dpi. |
| [embed_full_fonts](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/) | Egenskapen bestämmer om hela teckensnittsfilen ska bäddas in i PDF:en istället för en delmängd. |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/fallback_page_size/) | Reservsidans storlek. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/format/) | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/margin_settings/) | Marginalinställningarna som tillämpas under PDF-konvertering. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/orientation_settings/) | Orienteringsinställningarna. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/page_number/) | Sidnumret att börja konverteringen från. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages/) | Listan över sidindex som ska konverteras; ange för att konvertera specifika sidor. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages_count/) | Antalet sidor som ska konverteras med start från `page_number`. |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/password/) | Lösenordet som används för att skydda det konverterade dokumentet. |
| [pdf_options](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pdf_options/) | PDF-specifika konverteringsalternativ. |
| [resize_mode](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/resize_mode/) | Storleksändringsläget anger hur innehållet ska skalas när sidstorleken ändras. Standard är AlignTopLeft (ingen skalning). |
| [rotate](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/rotate/) | Sidrotationen. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/size_settings/) | Sidstorleksinställningarna som används under PDF-konvertering. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/watermark/) | Specifika alternativ för vattenstämpeln. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
Uppgiftsguider som använder `PdfConvertOptions`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### Se även
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
