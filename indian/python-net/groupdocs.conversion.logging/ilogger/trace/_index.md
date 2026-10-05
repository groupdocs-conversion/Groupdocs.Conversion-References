---
title: "trace विधि"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "ऐप्लिकेशन प्रवाह के बारे में सामान्यतः उपयोगी जानकारी प्रदान करने वाला ट्रेस लॉग संदेश लिखता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.logging/ilogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

ऐप्लिकेशन प्रवाह के बारे में सामान्यतः उपयोगी जानकारी प्रदान करने वाला ट्रेस लॉग संदेश लिखता है।

```python
def trace(self, message):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| message | `str` | यह ट्रेस संदेश। |

### उदाहरण

```python
from groupdocs.conversion.logging import ConsoleLogger

logger = ConsoleLogger()
logger.trace("Conversion started")
```

### साथ ही देखें
* class [`ILogger`](/conversion/python-net/groupdocs.conversion.logging/ilogger/)
