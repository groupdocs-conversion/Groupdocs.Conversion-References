---
title: "Metodo get_document_info"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Recupera le informazioni del documento di origine, inclusi il conteggio delle pagine e altre proprietà specifiche del tipo di file."
type: docs
url: /it/python-net/groupdocs.conversion/converter/get_document_info/
is_root: false
weight: 1080
---


## get_document_info

Recupera le informazioni del documento di origine, inclusi il conteggio delle pagine e altre proprietà specifiche del tipo di file.

Scopri di più sul documento convertito – tipo di file, numero di pagine, data di creazione e molte altre proprietà specifiche del formato:
- How to get document info (https://docs.groupdocs.com/display/conversionnet/Get+document+info)

```python
def get_document_info(self):
    ...
```

**Returns:** Document information as `IDocumentInfo`.

### Esempio

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Vedi anche
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
