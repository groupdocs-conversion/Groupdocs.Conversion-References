---
title: "Klassen ConsoleLogger"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Tillhandahåller en konsolloggningsimplementation."
type: docs
url: /sv/python-net/groupdocs.conversion.logging/consolelogger/
is_root: false
weight: 10
---


## ConsoleLogger class

Tillhandahåller en konsolloggningsimplementation.

Typen ConsoleLogger exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.logging/consolelogger/__init__/) |  |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [error](/conversion/python-net/groupdocs.conversion.logging/consolelogger/error/#message-exception) | Skriver felmeddelande till loggen. |
| [error_file](/conversion/python-net/groupdocs.conversion.logging/consolelogger/error_file/) |  |
| [error_string](/conversion/python-net/groupdocs.conversion.logging/consolelogger/error_string/) |  |
| [trace](/conversion/python-net/groupdocs.conversion.logging/consolelogger/trace/#message) | Skriver ett spårningsmeddelande i loggen som ger allmänt användbar information om applikationsflödet. |
| [trace_file](/conversion/python-net/groupdocs.conversion.logging/consolelogger/trace_file/) |  |
| [trace_string](/conversion/python-net/groupdocs.conversion.logging/consolelogger/trace_string/) |  |
| [warning](/conversion/python-net/groupdocs.conversion.logging/consolelogger/warning/#message) | Skriver ett varningsmeddelande i loggen. |
| [warning_file](/conversion/python-net/groupdocs.conversion.logging/consolelogger/warning_file/) |  |
| [warning_string](/conversion/python-net/groupdocs.conversion.logging/consolelogger/warning_string/) |  |

### Exempel

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()
with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Se även
* module [`groupdocs.conversion.logging`](/conversion/python-net/groupdocs.conversion.logging/)
