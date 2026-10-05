---
title: "Methode get_document_info"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Ruft Informationen zum Quelldokument ab, einschließlich Seitenzahl und anderer eigenschaftsspezifischer Details des Dateityps."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Ruft Informationen zum Quelldokument ab, einschließlich Seitenzahl und anderer eigenschaftsspezifischer Details des Dateityps.

```python
def get_document_info(self):
    ...
```

**Returns:** DocumentInfo: An object containing details about the source document, such as format, page count, creation date, size, and type‑specific properties.

### Beispiel

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Siehe auch
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
