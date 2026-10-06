---
title: "classe ConsoleLogger"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Fornisce un'implementazione del logger console."
type: docs
url: /it/python-net/groupdocs.conversion.logging/consolelogger/
is_root: false
weight: 10
---


## ConsoleLogger class

Fornisce un'implementazione del logger console.

Il tipo ConsoleLogger espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.logging/consolelogger/__init__/) |  |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [error](/conversion/python-net/groupdocs.conversion.logging/consolelogger/error/#message-exception) | Scrive un messaggio di log di errore. |
| [error_file](/conversion/python-net/groupdocs.conversion.logging/consolelogger/error_file/) |  |
| [error_string](/conversion/python-net/groupdocs.conversion.logging/consolelogger/error_string/) |  |
| [trace](/conversion/python-net/groupdocs.conversion.logging/consolelogger/trace/#message) | Scrive un messaggio di log di traccia che fornisce informazioni generalmente utili sul flusso dell'applicazione. |
| [trace_file](/conversion/python-net/groupdocs.conversion.logging/consolelogger/trace_file/) |  |
| [trace_string](/conversion/python-net/groupdocs.conversion.logging/consolelogger/trace_string/) |  |
| [warning](/conversion/python-net/groupdocs.conversion.logging/consolelogger/warning/#message) | Scrive un messaggio di log di avviso. |
| [warning_file](/conversion/python-net/groupdocs.conversion.logging/consolelogger/warning_file/) |  |
| [warning_string](/conversion/python-net/groupdocs.conversion.logging/consolelogger/warning_string/) |  |

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
* module [`groupdocs.conversion.logging`](/conversion/python-net/groupdocs.conversion.logging/)
