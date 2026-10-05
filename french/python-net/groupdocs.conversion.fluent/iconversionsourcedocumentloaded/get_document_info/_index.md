---
title: "Méthode get_document_info"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Récupère les informations du document source, y compris le nombre de pages et d'autres propriétés spécifiques au type de fichier."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Récupère les informations du document source, y compris le nombre de pages et d'autres propriétés spécifiques au type de fichier.

```python
def get_document_info(self):
    ...
```

**Returns:** DocumentInfo: An object containing details such as format, pages count, creation date, size, and other type‑specific attributes.

### Exemple

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Voir aussi
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
