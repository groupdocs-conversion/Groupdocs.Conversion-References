---
title: "PdfConvertOptions klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De opties voor conversie naar PDF-bestandstype."
type: docs
url: /nl/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/
is_root: false
weight: 340
---


## PdfConvertOptions class

De opties voor conversie naar PDF-bestandstype.

Het PdfConvertOptions-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/) | Initialiseert een nieuw [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) exemplaar. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/dpi/) | De gewenste pagina‑DPI na conversie. De standaardresolutie is 96 dpi. |
| [embed_full_fonts](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/) | De eigenschap bepaalt of het volledige lettertypebestand in de PDF wordt ingebed in plaats van een subset. |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/fallback_page_size/) | De fallback-pagina‑grootte. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/format/) | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/margin_settings/) | De marge‑instellingen die tijdens PDF‑conversie worden toegepast. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/orientation_settings/) | De oriëntatie‑instellingen. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/page_number/) | Het paginanummer waar de conversie moet beginnen. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages/) | De lijst met paginanummers die moeten worden geconverteerd; specificeer om specifieke pagina's te converteren. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages_count/) | Het aantal pagina's dat moet worden geconverteerd, beginnend bij `page_number`. |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/password/) | Het wachtwoord dat wordt gebruikt om het geconverteerde document te beveiligen. |
| [pdf_options](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pdf_options/) | De PDF‑specifieke conversie‑opties. |
| [resize_mode](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/resize_mode/) | De resize-modus specificeert hoe inhoud moet worden geschaald wanneer de paginagrootte wordt gewijzigd. Standaard is AlignTopLeft (geen schaling). |
| [rotate](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/rotate/) | De paginaverdraaiing. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/size_settings/) | De paginagrootte‑instellingen die tijdens PDF‑conversie worden gebruikt. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/watermark/) | De watermerk‑specifieke opties. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
Taakgidsen die `PdfConvertOptions` gebruiken:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### Zie ook
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
