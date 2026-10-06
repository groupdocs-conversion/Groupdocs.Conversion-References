---
title: "Metodo get_document_info"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Recupera le informazioni del documento sorgente, inclusi il conteggio delle pagine e altre proprietà specifiche del tipo di file."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/get_document_info/
is_root: false
weight: 1010
---


## get_document_info

Recupera le informazioni del documento sorgente, inclusi il conteggio delle pagine e altre proprietà specifiche del tipo di file.

```python
def get_document_info(self):
    ...
```

### Esempio

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Vedi anche
* class [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/)
