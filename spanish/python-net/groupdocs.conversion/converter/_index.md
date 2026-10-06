---
title: "Clase Converter"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Representa la clase principal que controla el proceso de conversión de documentos."
type: docs
url: /es/python-net/groupdocs.conversion/converter/
is_root: false
weight: 80
---


## Converter class

Representa la clase principal que controla el proceso de conversión de documentos.

El tipo Converter expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider) | Inicializa una nueva instancia de Converter. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings) | Inicializa una nueva instancia de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings) | Inicializa una nueva instancia de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings-events) | Inicializa un nuevo Converter con eventos de conversión explícitos. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings-events) | Inicializa una nueva instancia de Converter con eventos de conversión explícitos. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path) | Inicializa una nueva instancia de Converter. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings) | Inicializa una nueva instancia de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings) | Inicializa una nueva instancia de la clase [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings-events) | Inicializa un nuevo Converter con eventos de conversión explícitos. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings-events) | Inicializa un nuevo Converter con eventos de conversión explícitos. |

### Métodos
| Método | Descripción |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Convierte el documento de origen y guarda el documento convertido completo. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Convierte el documento de origen y guarda todo el documento convertido. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Convierte el documento de origen y guarda todo el documento convertido. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Convierte el documento de origen y guarda todo el documento convertido. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#file_path-convert_options) | Convierte el documento de origen y guarda todo el documento convertido. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Convierte el documento de origen y guarda el documento convertido página por página. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Convierte el documento de origen y guarda el documento convertido página por página. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Convierte el documento de origen y guarda el documento convertido página por página. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Convierte el documento de origen y guarda el documento convertido página por página. |
| [convert_convert_options](/conversion/python-net/groupdocs.conversion/converter/convert_convert_options/) |  |
| [convert_file](/conversion/python-net/groupdocs.conversion/converter/convert_file/) |  |
| [convert_func](/conversion/python-net/groupdocs.conversion/converter/convert_func/) |  |
| [convert_string](/conversion/python-net/groupdocs.conversion/converter/convert_string/) |  |
| [dispose](/conversion/python-net/groupdocs.conversion/converter/dispose/) | Libera recursos. |
| [get_all_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_all_possible_conversions/) | Obtiene todas las conversiones compatibles. |
| [get_document_info](/conversion/python-net/groupdocs.conversion/converter/get_document_info/) | Recupera la información del documento de origen, incluido el recuento de páginas y otras propiedades específicas del tipo de archivo. |
| [get_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions/) | Recupera las conversiones posibles para el documento de origen. |
| [get_possible_conversions_by_extension](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions_by_extension/#extension) | Obtiene las conversiones compatibles para la extensión de documento proporcionada. |
| [is_document_password_protected](/conversion/python-net/groupdocs.conversion/converter/is_document_password_protected/) | Comprueba si el documento de origen está protegido con contraseña. |

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("sample.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
Guías de tareas que usan `Converter`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Get Possible Conversions](/conversion/python-net/guides/get-possible-conversions/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)
* [Getting Document Information](/conversion/python-net/guides/getting-document-info/)

### Ver también
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
