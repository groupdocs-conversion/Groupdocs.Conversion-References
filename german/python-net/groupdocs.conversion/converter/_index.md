---
title: "Converter Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Stellt die Hauptklasse dar, die den Dokumentkonvertierungsprozess steuert."
type: docs
url: /de/python-net/groupdocs.conversion/converter/
is_root: false
weight: 80
---


## Converter class

Stellt die Hauptklasse dar, die den Dokumentkonvertierungsprozess steuert.

Der Typ Converter stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider) | Initialisiert eine neue Instanz von Converter. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings) | Initialisiert eine neue [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) Instanz. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings) | Initialisiert eine neue [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) Instanz. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings-events) | Initialisiert einen neuen Converter mit expliziten Konvertierungsereignissen. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings-events) | Initialisiert eine neue Converter-Instanz mit expliziten Konvertierungsereignissen. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path) | Initialisiert eine neue Converter-Instanz. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings) | Initialisiert eine neue [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) Instanz. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings) | Initialisiert eine neue Instanz der [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) Klasse. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings-events) | Initialisiert einen neuen Converter mit expliziten Konvertierungsereignissen. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings-events) | Initialisiert einen neuen Converter mit expliziten Konvertierungsereignissen. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Konvertiert das Quelldokument und speichert das gesamte konvertierte Dokument. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Konvertiert das Quelldokument und speichert das gesamte konvertierte Dokument. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Konvertiert das Quelldokument und speichert das gesamte konvertierte Dokument. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Konvertiert das Quelldokument und speichert das gesamte konvertierte Dokument. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#file_path-convert_options) | Konvertiert das Quelldokument und speichert das gesamte konvertierte Dokument. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Konvertiert das Quelldokument und speichert das konvertierte Dokument Seite für Seite. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Konvertiert das Quelldokument und speichert das konvertierte Dokument Seite für Seite. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Konvertiert das Quelldokument und speichert das konvertierte Dokument Seite für Seite. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Konvertiert das Quelldokument und speichert das konvertierte Dokument Seite für Seite. |
| [convert_convert_options](/conversion/python-net/groupdocs.conversion/converter/convert_convert_options/) |  |
| [convert_file](/conversion/python-net/groupdocs.conversion/converter/convert_file/) |  |
| [convert_func](/conversion/python-net/groupdocs.conversion/converter/convert_func/) |  |
| [convert_string](/conversion/python-net/groupdocs.conversion/converter/convert_string/) |  |
| [dispose](/conversion/python-net/groupdocs.conversion/converter/dispose/) | Gibt Ressourcen frei. |
| [get_all_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_all_possible_conversions/) | Ermittelt alle unterstützten Konvertierungen. |
| [get_document_info](/conversion/python-net/groupdocs.conversion/converter/get_document_info/) | Ruft Informationen zum Quelldokument ab, einschließlich Seitenzahl und anderer eigenschaftsspezifischer Angaben zum Dateityp. |
| [get_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions/) | Ruft mögliche Konvertierungen für das Quell-Dokument ab. |
| [get_possible_conversions_by_extension](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions_by_extension/#extension) | Ermittelt unterstützte Konvertierungen für die angegebene Dokumenterweiterung. |
| [is_document_password_protected](/conversion/python-net/groupdocs.conversion/converter/is_document_password_protected/) | Prüft, ob das Quelldokument passwortgeschützt ist. |

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("sample.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
Aufgabenleitfäden, die `Converter` verwenden:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Get Possible Conversions](/conversion/python-net/guides/get-possible-conversions/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)
* [Getting Document Information](/conversion/python-net/guides/getting-document-info/)

### Siehe auch
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
