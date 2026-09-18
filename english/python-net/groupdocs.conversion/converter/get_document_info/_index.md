---
title: get_document_info method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Retrieves source document info, including page count and other properties specific to the file type."
type: docs
url: /python-net/groupdocs.conversion/converter/get_document_info/
is_root: false
weight: 1080
---


## get_document_info

Retrieves source document info, including page count and other properties specific to the file type.

Learn more about converted document – file type, pages count, creation date and many other format‑specific properties:
- How to get document info (https://docs.groupdocs.com/display/conversionnet/Get+document+info)

```python
def get_document_info(self):
    ...
```

**Returns:** Document information as `IDocumentInfo`.

### Example

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### See Also
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
