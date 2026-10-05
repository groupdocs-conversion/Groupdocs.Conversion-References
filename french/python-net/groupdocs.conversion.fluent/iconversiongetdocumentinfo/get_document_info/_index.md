---
title: "Méthode get_document_info"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Récupère les informations du document source, y compris le nombre de pages et d'autres propriétés spécifiques au type de fichier."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/get_document_info/
is_root: false
weight: 1010
---


## get_document_info

Récupère les informations du document source, y compris le nombre de pages et d'autres propriétés spécifiques au type de fichier.

```python
def get_document_info(self):
    ...
```

### Exemple

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Voir aussi
* class [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/)
