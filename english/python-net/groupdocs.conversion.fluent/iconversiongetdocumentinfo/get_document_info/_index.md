---
title: get_document_info method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Retrieves source document information, including page count and other properties specific to the file type."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/get_document_info/
is_root: false
weight: 1010
---


## get_document_info

Retrieves source document information, including page count and other properties specific to the file type.

```python
def get_document_info(self):
    ...
```

### Example

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### See Also
* class [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/)
