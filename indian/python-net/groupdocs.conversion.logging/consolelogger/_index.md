---
title: "ConsoleLogger क्लास"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "कंसोल लॉगर कार्यान्वयन प्रदान करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.logging/consolelogger/
is_root: false
weight: 10
---


## ConsoleLogger class

कंसोल लॉगर कार्यान्वयन प्रदान करता है।

ConsoleLogger प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.logging/consolelogger/__init__/) |  |

### विधियाँ
| विधि | विवरण |
| :- | :- |
| [error](/conversion/python-net/groupdocs.conversion.logging/consolelogger/error/#message-exception) | त्रुटि लॉग संदेश लिखता है। |
| [error_file](/conversion/python-net/groupdocs.conversion.logging/consolelogger/error_file/) |  |
| [error_string](/conversion/python-net/groupdocs.conversion.logging/consolelogger/error_string/) |  |
| [trace](/conversion/python-net/groupdocs.conversion.logging/consolelogger/trace/#message) | ऐप्लिकेशन प्रवाह के बारे में सामान्यतः उपयोगी जानकारी प्रदान करने वाला ट्रेस लॉग संदेश लिखता है। |
| [trace_file](/conversion/python-net/groupdocs.conversion.logging/consolelogger/trace_file/) |  |
| [trace_string](/conversion/python-net/groupdocs.conversion.logging/consolelogger/trace_string/) |  |
| [warning](/conversion/python-net/groupdocs.conversion.logging/consolelogger/warning/#message) | एक चेतावनी लॉग संदेश लिखता है। |
| [warning_file](/conversion/python-net/groupdocs.conversion.logging/consolelogger/warning_file/) |  |
| [warning_string](/conversion/python-net/groupdocs.conversion.logging/consolelogger/warning_string/) |  |

### उदाहरण

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()
with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### साथ ही देखें
* module [`groupdocs.conversion.logging`](/conversion/python-net/groupdocs.conversion.logging/)
