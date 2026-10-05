---
title: "classe ConverterSettings"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Définit les paramètres pour personnaliser le comportement du Convertisseur."
type: docs
url: /fr/python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

Définit les paramètres pour personnaliser le comportement du Convertisseur.

Le type ConverterSettings expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | Initialise une nouvelle instance de ConverterSettings avec les valeurs par défaut. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | L'implémentation du cache utilisée pour stocker les résultats de conversion. |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | Les chemins des répertoires de polices personnalisées. |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | L'implémentation du listener du convertisseur utilisée pour surveiller l'état et la progression de la conversion, avec ses callbacks Started, Progress et Completed transmis à [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), et [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) pendant la construction de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | L'implémentation du logger utilisée pour consigner le processus de conversion. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | Le gestionnaire d'événement pour la compression terminée. |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | Le gestionnaire d'événement invoqué lorsque la conversion par page échoue. |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | Le gestionnaire d'événement invoqué lorsqu'une conversion échoue. |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | Le convertisseur parcourt les répertoires de polices de manière récursive lorsqu'il est réglé sur True. |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | Le dossier temporaire utilisé pour la conversion. |

### Exemple

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Voir aussi
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
