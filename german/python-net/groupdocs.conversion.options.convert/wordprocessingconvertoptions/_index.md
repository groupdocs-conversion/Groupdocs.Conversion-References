---
title: "WordProcessingConvertOptions Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die Optionen für die Konvertierung zum WordProcessing-Dateityp."
type: docs
url: /de/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
is_root: false
weight: 620
---


## WordProcessingConvertOptions class

Die Optionen für die Konvertierung zum WordProcessing-Dateityp.

Der WordProcessingConvertOptions Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/__init__/) | Initialisiert eine neue Instanz von [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/). |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi/) | Die gewünschte Seiten-DPI nach der Konvertierung. Die Standardauflösung beträgt 96 dpi. |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallback_page_size/) | Die alternative Seitengröße. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/format/) | Der gewünschte Dateityp, in den das Eingabedokument konvertiert werden soll. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/margin_settings/) | Die Rand-Einstellungen für die Konvertierung, dargestellt durch [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/). |
| [markdown_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdown_options/) | Die Markdown-Konvertierungsoptionen. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/orientation_settings/) | Die Orientierungseinstellungen. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/page_number/) | Die Seitenzahl, ab der die Konvertierung beginnen soll. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages/) | Die Liste der Seitenindizes, die konvertiert werden sollen. Sollte angegeben werden, um bestimmte Seiten zu konvertieren. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pages_count/) | Die Anzahl der Seiten, die ab `PageNumber` konvertiert werden sollen. |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/password/) | Das Passwort, das zum Schutz des konvertierten Dokuments verwendet wird. |
| [pdf_recognition_mode](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdf_recognition_mode/) | Der PDF-Erkennungsmodus, der für die Konvertierung verwendet wird und [`IPdfRecognitionModeOptions.pdf_recognition_mode`](/conversion/python-net/groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions/pdf_recognition_mode/) implementiert. |
| [rtf_options](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtf_options/) | Die RTF-spezifischen Konvertierungsoptionen. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/size_settings/) | Die Größeneinstellungen für die Konvertierung. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/watermark/) | Die spezifischen Optionen für das Wasserzeichen. |
| [zoom](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom/) | Der Zoom‑Level in Prozent. |

### Beispiel

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
Aufgabenleitfäden, die `WordProcessingConvertOptions` verwenden:

* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)

### Siehe auch
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
