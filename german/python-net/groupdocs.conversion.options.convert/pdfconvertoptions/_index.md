---
title: "Klasse PdfConvertOptions"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die Optionen für die Konvertierung zum PDF-Dateityp."
type: docs
url: /de/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/
is_root: false
weight: 340
---


## PdfConvertOptions class

Die Optionen für die Konvertierung zum PDF-Dateityp.

Der Typ PdfConvertOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/) | Initialisiert eine neue [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) Instanz. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/dpi/) | Die gewünschte Seiten-DPI nach der Konvertierung. Die Standardauflösung beträgt 96 dpi. |
| [embed_full_fonts](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/) | Die Eigenschaft bestimmt, ob die vollständige Schriftdatei in das PDF eingebettet wird anstatt eines Teilsets. |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/fallback_page_size/) | Die alternative Seitengröße. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/format/) | Der gewünschte Dateityp, in den das Eingabedokument konvertiert werden soll. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/margin_settings/) | Die Rand-Einstellungen, die während der PDF-Konvertierung angewendet werden. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/orientation_settings/) | Die Orientierungseinstellungen. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/page_number/) | Die Seitenzahl, ab der die Konvertierung beginnen soll. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages/) | Die Liste der Seitenindizes, die konvertiert werden sollen; geben Sie sie an, um bestimmte Seiten zu konvertieren. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages_count/) | Die Anzahl der Seiten, die ab `page_number` konvertiert werden sollen. |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/password/) | Das Passwort, das zum Schutz des konvertierten Dokuments verwendet wird. |
| [pdf_options](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pdf_options/) | Die PDF-spezifischen Konvertierungsoptionen. |
| [resize_mode](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/resize_mode/) | Der Skalierungsmodus gibt an, wie der Inhalt skaliert werden soll, wenn die Seitengröße geändert wird. Standard ist AlignTopLeft (keine Skalierung). |
| [rotate](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/rotate/) | Die Seitenrotation. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/size_settings/) | Die Seitengrößeneinstellungen, die während der PDF-Konvertierung verwendet werden. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/watermark/) | Die spezifischen Optionen für das Wasserzeichen. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
Aufgabenleitfäden, die `PdfConvertOptions` verwenden:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### Siehe auch
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
