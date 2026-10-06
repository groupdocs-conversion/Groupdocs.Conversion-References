---
title: "get_document_info método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Recupera la información del documento de origen, incluido el recuento de páginas y otras propiedades específicas del tipo de archivo."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Recupera la información del documento de origen, incluido el recuento de páginas y otras propiedades específicas del tipo de archivo.

```python
def get_document_info(self):
    ...
```

**Returns:** DocumentInfo: An object containing details such as format, pages count, creation date, size, and other type‑specific attributes.

### Ejemplo

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Ver también
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
