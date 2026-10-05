---
title: "Méthode get_document_info"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Récupère les informations du document source, y compris le nombre de pages et d'autres propriétés spécifiques au type de fichier."
type: docs
url: /fr/python-net/groupdocs.conversion/converter/get_document_info/
is_root: false
weight: 1080
---


## get_document_info

Récupère les informations du document source, y compris le nombre de pages et d'autres propriétés spécifiques au type de fichier.

En savoir plus sur le document converti – type de fichier, nombre de pages, date de création et de nombreuses autres propriétés spécifiques au format :
- How to get document info (https://docs.groupdocs.com/display/conversionnet/Get+document+info)

```python
def get_document_info(self):
    ...
```

**Returns:** Document information as `IDocumentInfo`.

### Exemple

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Voir aussi
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
