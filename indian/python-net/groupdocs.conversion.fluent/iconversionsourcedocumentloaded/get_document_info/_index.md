---
title: "get_document_info मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "स्रोत दस्तावेज़ की जानकारी प्राप्त करता है, जिसमें पृष्ठ गिनती और फ़ाइल प्रकार के विशिष्ट अन्य गुण शामिल हैं।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

स्रोत दस्तावेज़ की जानकारी प्राप्त करता है, जिसमें पृष्ठ गिनती और फ़ाइल प्रकार के विशिष्ट अन्य गुण शामिल हैं।

```python
def get_document_info(self):
    ...
```

**Returns:** DocumentInfo: An object containing details such as format, pages count, creation date, size, and other type‑specific attributes.

### उदाहरण

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### साथ ही देखें
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
