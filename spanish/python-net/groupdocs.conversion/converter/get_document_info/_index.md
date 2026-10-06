---
title: "get_document_info método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Recupera la información del documento de origen, incluido el recuento de páginas y otras propiedades específicas del tipo de archivo."
type: docs
url: /es/python-net/groupdocs.conversion/converter/get_document_info/
is_root: false
weight: 1080
---


## get_document_info

Recupera la información del documento de origen, incluido el recuento de páginas y otras propiedades específicas del tipo de archivo.

Obtén más información sobre el documento convertido – tipo de archivo, número de páginas, fecha de creación y muchas otras propiedades específicas del formato:
- How to get document info (https://docs.groupdocs.com/display/conversionnet/Get+document+info)

```python
def get_document_info(self):
    ...
```

**Returns:** Document information as `IDocumentInfo`.

### Ejemplo

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Ver también
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
