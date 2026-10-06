---
title: "Converter classe"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Rappresenta la classe principale che controlla il processo di conversione del documento."
type: docs
url: /it/python-net/groupdocs.conversion/converter/
is_root: false
weight: 80
---


## Converter class

Rappresenta la classe principale che controlla il processo di conversione del documento.

Il tipo Converter espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider) | Inizializza una nuova istanza di Converter. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings) | Inizializza una nuova istanza di [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings) | Inizializza una nuova istanza di [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings-events) | Inizializza un nuovo Converter con eventi di conversione espliciti. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings-events) | Inizializza una nuova istanza di Converter con eventi di conversione espliciti. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path) | Inizializza una nuova istanza di Converter. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings) | Inizializza una nuova istanza di [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings) | Inizializza una nuova istanza della classe [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings-events) | Inizializza un nuovo Converter con eventi di conversione espliciti. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings-events) | Inizializza un nuovo Converter con eventi di conversione espliciti. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Converte il documento di origine e salva l'intero documento convertito. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Converte il documento di origine e salva l'intero documento convertito. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Converte il documento di origine e salva l'intero documento convertito. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Converte il documento di origine e salva l'intero documento convertito. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#file_path-convert_options) | Converte il documento di origine e salva l'intero documento convertito. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Converte il documento di origine e salva il documento convertito pagina per pagina. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Converte il documento di origine e salva il documento convertito pagina per pagina. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Converte il documento di origine e salva il documento convertito pagina per pagina. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Converte il documento di origine e salva il documento convertito pagina per pagina. |
| [convert_convert_options](/conversion/python-net/groupdocs.conversion/converter/convert_convert_options/) |  |
| [convert_file](/conversion/python-net/groupdocs.conversion/converter/convert_file/) |  |
| [convert_func](/conversion/python-net/groupdocs.conversion/converter/convert_func/) |  |
| [convert_string](/conversion/python-net/groupdocs.conversion/converter/convert_string/) |  |
| [dispose](/conversion/python-net/groupdocs.conversion/converter/dispose/) | Rilascia le risorse. |
| [get_all_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_all_possible_conversions/) | Ottiene tutte le conversioni supportate. |
| [get_document_info](/conversion/python-net/groupdocs.conversion/converter/get_document_info/) | Recupera le informazioni del documento di origine, inclusi il conteggio delle pagine e altre proprietà specifiche del tipo di file. |
| [get_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions/) | Recupera le conversioni possibili per il documento di origine. |
| [get_possible_conversions_by_extension](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions_by_extension/#extension) | Ottiene le conversioni supportate per l'estensione del documento fornita. |
| [is_document_password_protected](/conversion/python-net/groupdocs.conversion/converter/is_document_password_protected/) | Verifica se il documento di origine è protetto da password. |

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("sample.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
Guide operative che utilizzano `Converter`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Get Possible Conversions](/conversion/python-net/guides/get-possible-conversions/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)
* [Getting Document Information](/conversion/python-net/guides/getting-document-info/)

### Vedi anche
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
