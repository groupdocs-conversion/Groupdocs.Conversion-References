---
title: "WordProcessingConvertOptions-klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Alternativen för konvertering till ordbehandlingsfiltyp."
type: docs
url: /sv/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
is_root: false
weight: 620
---


## WordProcessingConvertOptions class

Alternativen för konvertering till ordbehandlingsfiltyp.

WordProcessingConvertOptions-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/__init__/) | Initierar en ny instans av [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/). |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi/) | Den önskade sidans DPI efter konvertering. Standardupplösningen är 96 dpi. |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallback_page_size/) | Reservsidans storlek. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/format/) | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/margin_settings/) | Marginalinställningarna för konverteringen, representerade av [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/). |
| [markdown_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdown_options/) | Markdown‑konverteringsalternativen. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/orientation_settings/) | Orienteringsinställningarna. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/page_number/) | Sidnumret att börja konverteringen från. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages/) | Listan med sidindex som ska konverteras. Ska specificeras för att konvertera specifika sidor. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages_count/) | Antalet sidor att konvertera med start från `PageNumber`. |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/password/) | Lösenordet som används för att skydda det konverterade dokumentet. |
| [pdf_recognition_mode](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdf_recognition_mode/) | PDF‑igenkänningsläget som används för konvertering, implementerar [`IPdfRecognitionModeOptions.pdf_recognition_mode`](/conversion/python-net/groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions/pdf_recognition_mode/). |
| [rtf_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtf_options/) | De RTF‑specifika konverteringsalternativen. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/size_settings/) | Storleksinställningarna för konverteringen. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/watermark/) | Specifika alternativ för vattenstämpeln. |
| [zoom](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom/) | Zoomnivån i procent. |

### Exempel

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
Uppgiftsguider som använder `WordProcessingConvertOptions`:

* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)

### Se även
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
