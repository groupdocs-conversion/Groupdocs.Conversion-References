---
title: "Converter klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Representerar huvudklassen som styr dokumentkonverteringsprocessen."
type: docs
url: /sv/python-net/groupdocs.conversion/converter/
is_root: false
weight: 80
---


## Converter class

Representerar huvudklassen som styr dokumentkonverteringsprocessen.

Den Converter-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider) | Initierar en ny instans av Converter. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings) | Initierar en ny [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) instans. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings) | Initierar en ny [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) instans. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings-events) | Initierar en ny Converter med explicita konverteringshändelser. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings-events) | Initierar en ny Converter-instans med explicita konverteringshändelser. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path) | Initierar en ny Converter-instans. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings) | Initierar en ny [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) instans. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings) | Initierar en ny instans av [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) klass. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings-events) | Initierar en ny Converter med explicita konverteringshändelser. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings-events) | Initierar en ny Converter med explicita konverteringshändelser. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Konverterar källdokumentet och sparar hela det konverterade dokumentet. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Konverterar källdokumentet och sparar hela det konverterade dokumentet. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Konverterar källdokumentet och sparar hela det konverterade dokumentet. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Konverterar källdokumentet och sparar hela det konverterade dokumentet. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#file_path-convert_options) | Konverterar källdokumentet och sparar hela det konverterade dokumentet. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Konverterar källdokumentet och sparar det konverterade dokumentet sida för sida. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Konverterar källdokumentet och sparar det konverterade dokumentet sida för sida. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Konverterar källdokumentet och sparar det konverterade dokumentet sida för sida. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Konverterar källdokumentet och sparar det konverterade dokumentet sida för sida. |
| [convert_convert_options](/conversion/python-net/groupdocs.conversion/converter/convert_convert_options/) |  |
| [convert_file](/conversion/python-net/groupdocs.conversion/converter/convert_file/) |  |
| [convert_func](/conversion/python-net/groupdocs.conversion/converter/convert_func/) |  |
| [convert_string](/conversion/python-net/groupdocs.conversion/converter/convert_string/) |  |
| [dispose](/conversion/python-net/groupdocs.conversion/converter/dispose/) | Frigör resurser. |
| [get_all_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_all_possible_conversions/) | Hämtar alla stödda konverteringar. |
| [get_document_info](/conversion/python-net/groupdocs.conversion/converter/get_document_info/) | Hämtar information om källdokumentet, inklusive sidantal och andra egenskaper specifika för filtypen. |
| [get_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions/) | Hämtar möjliga konverteringar för källdokumentet. |
| [get_possible_conversions_by_extension](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions_by_extension/#extension) | Hämtar stödda konverteringar för angiven dokumentändelse. |
| [is_document_password_protected](/conversion/python-net/groupdocs.conversion/converter/is_document_password_protected/) | Kontrollerar om källdokumentet är lösenordsskyddat. |

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("sample.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
Uppgiftsguider som använder `Converter`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Get Possible Conversions](/conversion/python-net/guides/get-possible-conversions/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)
* [Getting Document Information](/conversion/python-net/guides/getting-document-info/)

### Se även
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
