---
title: "Converter klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Stelt de hoofdklasse voor die het documentconversieproces beheert."
type: docs
url: /nl/python-net/groupdocs.conversion/converter/
is_root: false
weight: 80
---


## Converter class

Stelt de hoofdklasse voor die het documentconversieproces beheert.

Het Converter-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider) | Initialiseert een nieuw exemplaar van Converter. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings) | Initialiseert een nieuw [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) exemplaar. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings) | Initialiseert een nieuw [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) exemplaar. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings-events) | Initialiseert een nieuwe Converter met expliciete conversiegebeurtenissen. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings-events) | Initialiseert een nieuw Converter-exemplaar met expliciete conversiegebeurtenissen. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path) | Initialiseert een nieuw Converter-exemplaar. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings) | Initialiseert een nieuw [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) exemplaar. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings) | Initialiseert een nieuw exemplaar van de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) klasse. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings-events) | Initialiseert een nieuwe Converter met expliciete conversiegebeurtenissen. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings-events) | Initialiseert een nieuwe Converter met expliciete conversiegebeurtenissen. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Converteert het brondocument en slaat het volledige geconverteerde document op. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Converteert het brondocument en slaat het gehele geconverteerde document op. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Converteert het brondocument en slaat het gehele geconverteerde document op. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Converteert het brondocument en slaat het gehele geconverteerde document op. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#file_path-convert_options) | Converteert het brondocument en slaat het gehele geconverteerde document op. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Converteert het brondocument en slaat het geconverteerde document pagina voor pagina op. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Converteert het brondocument en slaat het geconverteerde document pagina voor pagina op. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Converteert het brondocument en slaat het geconverteerde document pagina voor pagina op. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Converteert het brondocument en slaat het geconverteerde document pagina voor pagina op. |
| [convert_convert_options](/conversion/python-net/groupdocs.conversion/converter/convert_convert_options/) |  |
| [convert_file](/conversion/python-net/groupdocs.conversion/converter/convert_file/) |  |
| [convert_func](/conversion/python-net/groupdocs.conversion/converter/convert_func/) |  |
| [convert_string](/conversion/python-net/groupdocs.conversion/converter/convert_string/) |  |
| [dispose](/conversion/python-net/groupdocs.conversion/converter/dispose/) | Geeft bronnen vrij. |
| [get_all_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_all_possible_conversions/) | Haalt alle ondersteunde conversies op. |
| [get_document_info](/conversion/python-net/groupdocs.conversion/converter/get_document_info/) | Haalt de informatie van het brondocument op, inclusief paginatelling en andere eigenschappen die specifiek zijn voor het bestandstype. |
| [get_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions/) | Haalt mogelijke conversies op voor het bron document. |
| [get_possible_conversions_by_extension](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions_by_extension/#extension) | Haalt ondersteunde conversies op voor de opgegeven documentextensie. |
| [is_document_password_protected](/conversion/python-net/groupdocs.conversion/converter/is_document_password_protected/) | Controleert of het brondocument met een wachtwoord is beveiligd. |

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("sample.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
Taakgidsen die `Converter` gebruiken:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Get Possible Conversions](/conversion/python-net/guides/get-possible-conversions/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)
* [Getting Document Information](/conversion/python-net/guides/getting-document-info/)

### Zie ook
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
