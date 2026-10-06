---
title: "WordProcessingConvertOptions klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De opties voor conversie naar WordProcessing-bestandstype."
type: docs
url: /nl/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
is_root: false
weight: 620
---


## WordProcessingConvertOptions class

De opties voor conversie naar WordProcessing-bestandstype.

Het type WordProcessingConvertOptions bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/__init__/) | Initialiseert een nieuw exemplaar van [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/). |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi/) | De gewenste pagina‑DPI na conversie. De standaardresolutie is 96 dpi. |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallback_page_size/) | De fallback-pagina‑grootte. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/format/) | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/margin_settings/) | De marge‑instellingen voor de conversie, weergegeven door [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/). |
| [markdown_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdown_options/) | De Markdown-conversie‑opties. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/orientation_settings/) | De oriëntatie‑instellingen. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/page_number/) | Het paginanummer waar de conversie moet beginnen. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages/) | De lijst met paginacijfers die moeten worden geconverteerd. Moet worden gespecificeerd om specifieke pagina's te converteren. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages_count/) | Het aantal pagina's dat moet worden geconverteerd, beginnend bij `PageNumber`. |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/password/) | Het wachtwoord dat wordt gebruikt om het geconverteerde document te beveiligen. |
| [pdf_recognition_mode](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdf_recognition_mode/) | De PDF‑herkenningsmodus die wordt gebruikt voor conversie, geïmplementeerd door [`IPdfRecognitionModeOptions.pdf_recognition_mode`](/conversion/python-net/groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions/pdf_recognition_mode/). |
| [rtf_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtf_options/) | De RTF‑specifieke conversie‑opties. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/size_settings/) | De grootte‑instellingen voor de conversie. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/watermark/) | De watermerk‑specifieke opties. |
| [zoom](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom/) | Het zoomniveau in procenten. |

### Voorbeeld

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
Taakgidsen die `WordProcessingConvertOptions` gebruiken:

* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)

### Zie ook
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
