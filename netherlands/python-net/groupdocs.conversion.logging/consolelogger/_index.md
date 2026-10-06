---
title: "ConsoleLogger klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Biedt een console-loggerimplementatie."
type: docs
url: /nl/python-net/groupdocs.conversion.logging/consolelogger/
is_root: false
weight: 10
---


## ConsoleLogger class

Biedt een console-loggerimplementatie.

Het ConsoleLogger-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.logging/consolelogger/__init__/) |  |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [error](/conversion/python-net/groupdocs.conversion.logging/consolelogger/error/#message-exception) | Schrijft een foutlogbericht. |
| [error_file](/conversion/python-net/groupdocs.conversion.logging/consolelogger/error_file/) |  |
| [error_string](/conversion/python-net/groupdocs.conversion.logging/consolelogger/error_string/) |  |
| [trace](/conversion/python-net/groupdocs.conversion.logging/consolelogger/trace/#message) | Schrijft een traceerlogbericht dat over het algemeen nuttige informatie over de applicatiestroom biedt. |
| [trace_file](/conversion/python-net/groupdocs.conversion.logging/consolelogger/trace_file/) |  |
| [trace_string](/conversion/python-net/groupdocs.conversion.logging/consolelogger/trace_string/) |  |
| [warning](/conversion/python-net/groupdocs.conversion.logging/consolelogger/warning/#message) | Schrijft een waarschuwingslogbericht. |
| [warning_file](/conversion/python-net/groupdocs.conversion.logging/consolelogger/warning_file/) |  |
| [warning_string](/conversion/python-net/groupdocs.conversion.logging/consolelogger/warning_string/) |  |

### Voorbeeld

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()
with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Zie ook
* module [`groupdocs.conversion.logging`](/conversion/python-net/groupdocs.conversion.logging/)
