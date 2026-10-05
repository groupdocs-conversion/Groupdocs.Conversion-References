---
title: "Classe Converter"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Représente la classe principale qui contrôle le processus de conversion de documents."
type: docs
url: /fr/python-net/groupdocs.conversion/converter/
is_root: false
weight: 80
---


## Converter class

Représente la classe principale qui contrôle le processus de conversion de documents.

Le type Converter expose les membres suivants:

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider) | Initialise une nouvelle instance de Converter. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings) | Initialise une nouvelle instance de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings) | Initialise une nouvelle instance de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-load_options-settings-events) | Initialise un nouveau Converter avec des événements de conversion explicites. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#source_stream_provider-settings-events) | Initialise une nouvelle instance de Converter avec des événements de conversion explicites. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path) | Initialise une nouvelle instance de Converter. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings) | Initialise une nouvelle instance de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings) | Initialise une nouvelle instance de la classe [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-load_options-settings-events) | Initialise un nouveau Converter avec des événements de conversion explicites. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#file_path-settings-events) | Initialise un nouveau Converter avec des événements de conversion explicites. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Convertit le document source et enregistre le document converti complet. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Convertit le document source et enregistre le document converti entier. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Convertit le document source et enregistre le document converti entier. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Convertit le document source et enregistre le document converti entier. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#file_path-convert_options) | Convertit le document source et enregistre le document converti entier. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options_provider) | Convertit le document source et enregistre le document converti page par page. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#target_stream_provider-convert_options) | Convertit le document source et enregistre le document converti page par page. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options-document_completed) | Convertit le document source et enregistre le document converti page par page. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#convert_options_provider-document_completed) | Convertit le document source et enregistre le document converti page par page. |
| [convert_convert_options](/conversion/python-net/groupdocs.conversion/converter/convert_convert_options/) |  |
| [convert_file](/conversion/python-net/groupdocs.conversion/converter/convert_file/) |  |
| [convert_func](/conversion/python-net/groupdocs.conversion/converter/convert_func/) |  |
| [convert_string](/conversion/python-net/groupdocs.conversion/converter/convert_string/) |  |
| [dispose](/conversion/python-net/groupdocs.conversion/converter/dispose/) | Libère les ressources. |
| [get_all_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_all_possible_conversions/) | Obtient toutes les conversions prises en charge. |
| [get_document_info](/conversion/python-net/groupdocs.conversion/converter/get_document_info/) | Récupère les informations du document source, y compris le nombre de pages et d'autres propriétés spécifiques au type de fichier. |
| [get_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions/) | Récupère les conversions possibles pour le document source. |
| [get_possible_conversions_by_extension](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions_by_extension/#extension) | Obtient les conversions prises en charge pour l'extension de document fournie. |
| [is_document_password_protected](/conversion/python-net/groupdocs.conversion/converter/is_document_password_protected/) | Vérifie si le document source est protégé par mot de passe. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("sample.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
Guides de tâches qui utilisent `Converter`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Get Possible Conversions](/conversion/python-net/guides/get-possible-conversions/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)
* [Getting Document Information](/conversion/python-net/guides/getting-document-info/)

### Voir aussi
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
