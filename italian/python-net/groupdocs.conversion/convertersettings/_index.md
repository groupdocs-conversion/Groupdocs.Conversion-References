---
title: "classe ConverterSettings"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Definisce le impostazioni per personalizzare il comportamento del Converter."
type: docs
url: /it/python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

Definisce le impostazioni per personalizzare il comportamento del Converter.

Il tipo ConverterSettings espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | Inizializza una nuova istanza di ConverterSettings con valori predefiniti. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | L'implementazione della cache utilizzata per memorizzare i risultati della conversione. |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | I percorsi delle directory dei font personalizzati. |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | L'implementazione del listener del convertitore usata per monitorare lo stato e l'avanzamento della conversione, con i suoi callback Started, Progress e Completed inoltrati a [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), e [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) durante la costruzione di [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | L'implementazione del logger usata per registrare il processo di conversione. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | Il gestore dell'evento per la compressione completata. |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | Il gestore dell'evento invocato quando la conversione per pagina fallisce. |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | Il gestore dell'evento invocato quando una conversione fallisce. |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | Il convertitore scansiona ricorsivamente le directory dei font quando impostato su True. |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | La cartella temporanea usata per la conversione. |

### Esempio

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Vedi anche
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
